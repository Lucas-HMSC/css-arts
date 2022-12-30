<template>
  <RouterView />
</template>

<script setup>
import { RouterView } from 'vue-router'
</script>

<style>
body {
  padding: 0;
  margin: 0;
  background-color: #212529;
  color: #f8f9fa;
  font-family: 'JetBrains Mono', monospace;
  font-size: 16px;
}

a {
  font-weight: 400;
  color: inherit;
  margin: 0.5rem 2rem;
  text-decoration: none;
}

a:hover {
  color: #bd68ee;
  transition: color 0.2s;
}
</style>