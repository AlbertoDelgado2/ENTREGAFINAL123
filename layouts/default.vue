<template>
    <div>
      <header class="flex justify-between mx-20 my-20">
        <div>logo</div>
    
          <div class="flex gap-7">
            <div class="boton"><button><NuxtLink to="/">home</NuxtLink></button></div>
            <div class="boton"><button><NuxtLink to="/about">about</NuxtLink></button></div>
            <div class="boton"><button><NuxtLink to="/products">products</NuxtLink></button></div>
          </div>

      </header>
    </div>
        <div>
        <slot />
        </div>
      </template>
 