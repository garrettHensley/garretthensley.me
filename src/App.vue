<script setup>
import HelloWorld from "./components/HelloWorld.vue";
</script>

<template>
  <HelloWorld msg="Vite + Vue" />
</template>

<style>
.logo {
  height: 6em;
  padding: 1.5em;
  will-change: filter;
  transition: filter 300ms;
}
.logo:hover {
  filter: drop-shadow(0 0 2em #646cffaa);
}
.logo.vue:hover {
  filter: drop-shadow(0 0 2em #42b883aa);
}
html body {
  background-color: #161a20;
  color: #ba2e55;
}
</style>
