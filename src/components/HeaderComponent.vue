<script setup lang="ts">
  import { RouterLink } from 'vue-router'
</script>

<template>
  <header>
    <img alt="Vue logo" class="logo" src="@/assets/logo.svg" width="125" height="125" />

    <div class="wrapper">
      <span>Strongberry</span>
      <nav>
        <RouterLink to="/">Home</RouterLink>
        <RouterLink to="/workout">Workout</RouterLink>
        <RouterLink to="/history">History</RouterLink>
        <RouterLink to="/about">About</RouterLink>
      </nav>
    </div>
  </header>
</template>

<style scoped>
</style>

