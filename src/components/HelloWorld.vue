<script setup>
import { ref } from "vue";

defineProps({
  msg: String,
});

const count = ref(0);
</script>

<template>
  <div>
    Hello! Site is currently under construction. In the meantime, please
    checkout my GitHub to see what I'm currently working on!
  </div>
  <h1>
    <a href="http://github.com/garretthensley" target="_blank">My GitHub</a>
  </h1>
</template>

<style scoped>
.read-the-docs {
  color: #888;
}
</style>
