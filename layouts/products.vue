<template>
<div class="ms-10 my-10 text-4x1 font-thin text-purple-500">
    <NuxtLink to="/">FakeStore</NuxtLink>
</div>
<slot />
<div class="mx-10 my10 pt-5 flex fap-7 font-bold shadow-inner">
            <button><NuxtLink to="/">home</NuxtLink></button>
            <button><NuxtLink to="/">about</NuxtLink></button>
            <button><NuxtLink to="/">products</NuxtLink></button>
 </div>

</template>
<script setup>
</script>