<script setup>
import { RouterLink, RouterView } from 'vue-router';
</script>

<template>
  <header class="bg-cyan-300 flex justify-center">
    <nav class="flex justify-between w-96">
      <RouterLink class="bg-lime-300" to="/">Home</RouterLink>
      <RouterLink class="bg-lime-300" to="/about">About</RouterLink>
    </nav>
  </header>

  <RouterView />
</template>

<style scoped></style>
