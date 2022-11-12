<script setup lang="ts">
import { RouterLink } from "vue-router";
</script>

<template>
  <div class="greetings">
    <h1 class="pb-8 text-3xl text-center text-teal-600">Latlay!</h1>
    <nav class="text-center text-xs w-full">
      <RouterLink to="/" class="border-r pr-4">Home</RouterLink>
      <RouterLink to="/about" class="pl-4">About</RouterLink>
    </nav>
  </div>
</template>

<style scoped>
nav a.router-link-exact-active {
  color: #14b8a6;
}
</style>
