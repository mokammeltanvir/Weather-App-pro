<template>
  <header class="sticky top-0 bg-weather-primary shadow-lg">
  <nav class="container flex flex-col sm:flex-row items-center gap-4 text-white py-6">
    <RouterLink :to="{name: 'home'}">
    <div class="flex items-center gap-3 flex-1">
    <i class="fa-solid fa-cloud-sun text-2xl"></i>
    <h1 class="text-2xl font-bold">Weather App</h1>
    </div>      
    </RouterLink>
    <div class="flex flex-1 justify-end gap-3">
    <i class="fa-solid fa-circle-info text-xl hover:text-weather-secondary duration-150 cursor-pointer"></i>
    <i class="fa-solid fa-square-plus text-xl hover:text-weather-secondary duration-150 cursor-pointer"></i>
    </div>
  </nav>

  </header>
</template>

<script setup>
import {RouterLink} from 'vue-router'
</script>
