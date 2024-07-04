<script setup>
import HelloWorld from './components/HelloWorld.vue'
</script>

<template>
  <h1 class="logo">CIAO QUESTO E' UN TITOLONEEE</h1>
  <span>psss....passaci sopra</span>
</template>

<style scoped>
.logo {
  height: 6em;
  padding: 1.5em;
  will-change: filter;
  transition: filter 300ms;
}

.logo:hover {
  filter: drop-shadow(0 0 1rem #646cffaa);
}

</style>
