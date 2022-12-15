<template>
  <h1>{{title}}</h1>
  <Counter />
</template>

<script setup lang="ts">
  import {ref} from "vue";
  import {Counter} from "./src";

  const title = ref('business');
</script>
