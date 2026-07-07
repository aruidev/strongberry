<script setup lang="ts">
import { RouterView } from 'vue-router';
import FooterComponent from './components/FooterComponent.vue';
import HeaderComponent from './components/HeaderComponent.vue';
</script>

<template>
  <div id="layout">
    <HeaderComponent />

    <main>
      <RouterView />
    </main>

    <FooterComponent />
  </div>
</template>

<style scoped>
</style>
