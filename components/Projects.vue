<script setup lang="ts">
</script>

<template>
  <section id="projects" class="min-h-screen p-10 bg-white">
    <h2 class="text-4xl font-bold mb-6">Projects</h2>
    <div class="grid grid-cols-1 sm:grid-cols-2 lg:grid-cols-3 gap-6">
      <div v-for="n in 6" :key="n" class="p-6 bg-gray-50 rounded-xl shadow hover:shadow-lg">
        <h3 class="text-xl font-semibold">Project {{ n }}</h3>
        <p class="text-gray-600 mt-2">Description for project {{ n }}</p>
      </div>
    </div>
  </section>
</template>
