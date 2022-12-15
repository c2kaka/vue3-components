<template>
  <div class="my-biz-counter">
    <div class="num-value">{{ num }}</div>
    <button @click="onClick">点击减1</button>
  </div>
</template>

<script lang="ts" setup>
import { ref } from 'vue';
const num = ref<number>(100);
const onClick = () => {
  num.value -= 1;
};
</script>
