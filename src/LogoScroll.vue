<script setup>
import LogoCarousel from './layouts/LogoCarousel.vue';
</script>

<template>
     <div class="relative inset-0 bg-black mt-50 md:mt-0">
    <LogoCarousel
      :logos="[
        '/images/comp1.png',
        '/images/comp2.png',
        '/images/comp3.png',
        '/images/comp4.png'
      ]"
      :speed="25"
    />
  </div>   



</template>