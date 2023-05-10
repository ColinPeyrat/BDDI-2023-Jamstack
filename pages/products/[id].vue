<template>
  <main>
    <h1>Produit #{{ id }}</h1>
    <nuxt-link to="/">Home</nuxt-link>
  </main>
</template>

<script setup lang="ts">
const route = useRoute()

const { id } = route.params
</script>