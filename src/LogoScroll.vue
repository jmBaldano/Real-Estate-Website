<script setup>
import LogoCarousel from './layouts/LogoCarousel.vue';
</script>

<template>
     <div class="relative inset-0 bg-black mt-50 md:mt-0">
    <LogoCarousel
      :logos="[
        '/Real-Estate-Website/images/comp1.png',
        '/Real-Estate-Website/images/comp2.png',
        '/Real-Estate-Website/images/comp3.png',
        '/Real-Estate-Website/images/comp4.png'
      ]"
      :speed="25"
    />
  </div>   



</template>