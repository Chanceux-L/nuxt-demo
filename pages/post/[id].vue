<script setup>
const route = useRoute();
</script>

<template>
  <h1>Welcome to the post {{ route.params.id }} page</h1>
</template>
