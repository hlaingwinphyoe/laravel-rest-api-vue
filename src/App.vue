<script setup>
import { RouterLink, RouterView } from 'vue-router'
</script>

<template>
  <header>
    <div class="mx-auto max-w-7xl">
      <nav class="p-2">
        <RouterLink to="/" class="px-4 py-2 mr-4 text-white bg-indigo-600 rounded hover:bg-indigo-800">Home</RouterLink>
        <RouterLink to="/skills" class="px-4 py-2 mr-4 text-white bg-indigo-600 rounded hover:bg-indigo-800">Skills</RouterLink>
      </nav>
    </div>
  </header>

  <main class="min-h-screen mx-auto max-w-7xl">
    <RouterView />
  </main>
</template>