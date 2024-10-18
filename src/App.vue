<script setup lang="ts">
import { ref } from "vue";
let msg = ref("Hello World");
</script>

<template>
  <div class="flex flex-col items-center justify-center h-screen">
    <a href="https://vuejs.org/" target="_blank">
      <img src="/vite.svg" class="logo vue" alt="Vue logo" />
    </a>
    <span>{{ msg }}</span>
  </div>
</template>

<style scoped>
.logo {
  height: 6em;
  padding: 1.5em;
  will-change: filter;
  transition: filter 300ms;
}
.logo.vue:hover {
  filter: drop-shadow(0 0 2em #42b883aa);
}
</style>
