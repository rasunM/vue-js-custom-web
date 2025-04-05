<template>
  <div class="flex flex-col items-center mt-10 mx-50">
    <h1 class="text-6xl font-bold mb-15 text-green-900">My Projects</h1>
    <div class="flex justify-between gap-10">
      <Card />
      <Card />
      <Card />
    </div>
  </div>
</template>
<script setup>
import Card from '../components/Card.vue';
</script>
