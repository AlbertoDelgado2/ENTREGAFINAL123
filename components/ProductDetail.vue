<template>
    <div class="grid grid-cols-2">
        <div>
<img :src="product.image" alt="">
    </div>
    <div>
        <h2>{{ product.title }}</h2>
        <p> {{ ProductCard.price }}</p>
        <h3>{{ product.desciption }}</h3>
    </div>
    </div>
</template>

<script setup>

</script>

<style lang="scss" scoped>

</style>