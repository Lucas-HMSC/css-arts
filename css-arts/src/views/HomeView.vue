<template>
  <main>
    <h1>CSS Arts</h1>
    <RouterLink to="spiderman">Spiderman</RouterLink>
  </main>
</template>

<script setup>
import { RouterLink } from 'vue-router'
</script>

<style scoped>
h1 {
  margin: 1.5rem;
  font-weight: 600;
  text-align: center;
}
</style>