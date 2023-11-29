<template>
  <h1>The User ID is {{ id }}</h1>
</template>

<script setup>
const nuxt = useNuxtApp();
const id = nuxt._route.params.id;
console.log(nuxt._route.params.id);
// const route = useRoute();
// console.log(route.params.id);
</script>
