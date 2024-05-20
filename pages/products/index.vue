<template>
    <div>
      <h1 class="text-3xl font-bold mx-10 my-10 tex text-lime-600">
      Productos
    </h1>
    <div class="grid grid-cols-4 gap-5 mx -10">
    </div>
    <div v-for="p in products"></div>
    <NuxtLink :to="`products/${p.id}`">{{ p.tittle }}</NuxtLink></div>
  </template>

<script setup>
definePageMeta({
  layout: "products"
})
const {data: products } = await useFetch ('https://fakestoreapi.com/products')
</script>

