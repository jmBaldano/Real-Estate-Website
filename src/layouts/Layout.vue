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
    <div class="relative ">
        <header class="fixed top-0 left-0 z-50 w-full bg-white">
            <nav class="flex items-center justify-between p-0 mx-auto text-sm text-center text-black pr-25">
                <div class="pt-0 ">
                    <a href="#Home"><img src="/images/logo.png"
                    class="block mx-auto max-w-[250px] md:max-w-[350px] h-auto pl-10 md:pl-20"></a>
                </div>
                <div class="hidden pb-3 m-0 space-x-20 text-black md:flex">
                    <a href="#Home" class="navBttn">HOME</a>
                    <a href="#About" class="navBttn">ABOUT</a>
                    <a href="#SearchListings" class="navBttn">LISTINGS</a>
                    <a href="#Services" class="navBttn">Services</a>
                    <a href="#Contact" class="navBttn">CONTACT</a>

                </div>
                <!-- hamburger design -->
                <button @click="toggleMenu" class="p-2 transition-colors rounded-full md:hidden hover:bg-white/10">

                    <div class="flex flex-col items-center justify-center cursor-pointer w-6 h-6 pl-40 md:pl-0">
                        <span class="block w-5 h-0.5 bg-black mt-1 transition-all duration-300" :class="{ 'rotate-45  translate-y-1.5': isMenuOpen }"></span>
                        <span class="block w-5 h-0.5 bg-black mt-1 transition-all duration-100" :class="{ 'opacity-0': isMenuOpen }"></span>
                        <span class="block w-5 h-0.5 bg-black mt-1 transition-all duration-500" :class="{ '-rotate-45 -translate-y-1.5': isMenuOpen }"></span>
                    </div>
                    
                </button>
            </nav>

    <!-- Mobile Menu Overlay -->
<div v-if="isMenuOpen" class="inset-0 z-50 fixe md:hidden" @click.self="closeMenu">

  <div class="fixed w-64 font-bold bg-white shadow-xl top-20 right-4 backdrop-blur-md rounded-2xl">
    <nav class="p-6 space-y-0">
      <a href="#Home" @click="closeMenu" class="block px-4 py-3 font-light text-gray-900 rounded-lg line ">HOME</a>
      <a href="#About" @click="closeMenu" class="block px-4 py-3 font-light text-gray-900 rounded-lg line ">ABOUT</a>
      <a href="#SearchListings" @click="closeMenu" class="block px-4 py-3 font-light text-gray-900 rounded-lg line ">LISTINGS</a>
      <a href="#Services" @click="closeMenu" class="block px-4 py-3 font-light text-gray-900 rounded-lg line ">SERVICES</a>
      <a href="#Contact" @click="closeMenu" class="block px-4 py-3 font-light text-gray-900 rounded-lg line ">CONTACT</a>
    </nav>
  </div>
</div>

           
            

        </header>
    </div>

    <main class="">
        <slot />
    </main>
</template>