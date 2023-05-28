<script setup lang="ts">
import { RouterLink } from 'vue-router'
</script>

<template>
  <nav>
    <!-- <img alt="realanimeschedule" class="logo" src="@/assets/logo.svg" width="100" height="50" /> -->
    <ul>
      <RouterLink to="/">Home</RouterLink>
      <RouterLink to="/about">About</RouterLink>
    </ul>
    <button class="btn btn-primary">Test</button>
  </nav>
</template>

<style scoped>
nav {
  background-color: #333;
  padding: 1rem;
  width: 100vw;
  margin: 0;
  display: flex;
  justify-content: space-between;
}

ul {
  display: flex;
  list-style: none;
  justify-content: space-between;
  margin: 0;
  padding: 0;
}
</style>
