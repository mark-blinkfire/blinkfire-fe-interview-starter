<template>
  <div class="home">
    <AppHeader />
    <DriversDashboard />
  </div>
</template>

<script setup>
import AppHeader from './AppHeader.vue'
import DriversDashboard from './DriversDashboard.vue'
</script>

<style scoped>
.home {
  color: #333;
  background-color: #f0f0f0;
  width: 100%;
  min-height: 100vh;
  padding: 0;
  margin: 0;
  display: flex;
  flex-direction: column;
}
</style>
