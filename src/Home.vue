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
  
    <!-- Background image -->
<div class="absolute inset-0 bg-center bg-cover"
     :style="{ backgroundImage: 'url(/images/bg.jpg)', backgroundAttachment: 'fixed' }">
</div>

<!-- Radial gradient overlay -->
<div class="absolute inset-0 bg-[radial-gradient(ellipse_at_center,transparent_60%,rgba(0,0,0,0.1)_100%)]"></div>

<!-- Dark overlay -->
<div class="absolute inset-0 bg-black/60"></div>

<!-- Content -->
<div class="absolute flex items-center justify-start min-h-screen w-[90%] md:w-[80%] lg:w-[70%] px-[5%] md:px-[8%] text-white">
  <div class="text-left">
    <p class="font-serif text-[6vw] md:text-[4vw] lg:text-[3vw] leading-tight">
      PAHRUMP REALTOR
    </p>
    <h1 class="pt-4 text-[3vw] md:text-[1.8vw] font-light">
      MARCI METZGER - THE RIDGE REALTY GROUP
    </h1>
    <button
      class="px-[8%] py-[2%] mt-[5%] text-[2.5vw] md:text-[1.2vw] tracking-widest text-white uppercase transition-all  outline-2 outline-white hover:bg-gray-300 hover:text-gray-900 hover:outline-0">
      Call now
    </button>
  </div>
</div>

  

</template>
