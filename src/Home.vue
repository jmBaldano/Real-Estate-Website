<script setup>
import { ref } from 'vue'
const isMenuOpen = ref(false)

const toggleMenu = () => {
  isMenuOpen.value = !isMenuOpen.value
}

const closeMenu = () => {
  isMenuOpen.value = false
}
</script>

<template>
  
    <div class="absolute inset-0 bg-center bg-cover"
      :style="{ backgroundImage: 'url(/images/bg.jpg)', backgroundAttachment: 'fixed' }"></div>
    <div class="absolute  inset-0 bg-[radial-gradient(ellipse_at_center,transparent_60%,rgba(0,0,0,0.1)_100%)]"></div>
    <!-- Dark overlay -->
<div class="absolute inset-0 bg-black/40"></div>
  

   <div class="absolute flex items-center justify-start min-h-screen px-6 pb-5 text-white md:px-16">
      <div class="text-left">
        <p class="font-serif text-3xl md:text-7xl">PAHRUMP REALTOR</p>
        <h1 class="pt-4 text-sm text-white font-base md:text-2xl">MARCI METZGER - THE RIDGE REALTY GROUP</h1>
        <button class="px-10 py-3 mt-10 ml-3 text-lg tracking-widest text-white uppercase transition border-2 font-base hover:border-0 hover:bg-gray-300 hover:text-gray-900">Call now</button>
      </div>
    </div>
  

</template>
