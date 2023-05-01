<template>
  <div>
    <Suspense>
      <AsyncCityView />
      <template #fallback>
      <i class="fa-sharp fa-solid fa-loader animate-spin"></i>
        <p>Loading...</p>
      </template>
    </Suspense>
  </div>
</template>

<script setup>
import AsyncCityView from "../components/AsyncCityView.vue";
</script>