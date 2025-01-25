<script setup lang="ts">  
  import GetLocation from './components/GetLocation.vue';
  import WeatherReport from './components/WeatherReport.vue';
</script>

<template>
  <GetLocation />
  <WeatherReport :coords="{ latitude: 0, longitude: 0 }" />
</template>

<style scoped>
</style>
