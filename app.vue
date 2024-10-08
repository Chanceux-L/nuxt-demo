<script setup lang="ts">
useHead({
  title: 'Chanceux Nuxt App',
  meta: [
    { name: 'description', content: 'Chanceux Nuxt App description' },
  ],
})
</script>

<template>
  <Alert>
    <span>This is an auto-imported component: Alert</span>
  </Alert>
  <div>
    <Nav />
    <NuxtPage />
  </div>
</template>
