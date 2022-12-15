<template>
  <div class="body">{{title}}</div>
</template>

<script setup lang="ts">
  import {ref} from "vue";

  const title = ref('example');
</script>
