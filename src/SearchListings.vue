<script setup>
import LogoCarousel from './layouts/LogoCarousel.vue';
</script>

<template>
  <div class="relative w-full h-[200px] sm:h-[500px] md:h-[350px]">
    <!-- Background image -->
    <div class="absolute inset-0 bg-center bg-cover bg-[url('/images/bg2.jpg')]"></div>
    <!-- Overlay -->
    <div class="absolute inset-0 bg-black/70"></div>

    <!-- Title -->
    <div class="relative text-4xl text-center h-[20%] flex items-center justify-center">
      <h1 class="font-serif text-white pt-[5%] text-xl sm:text-2xl md:text-4xl">Find Your Dream Home</h1>
    </div>

    <!-- Form container -->
    <div class="absolute w-[90%] sm:w-3/4 md:w-1/2 left-1/2 transform -translate-x-1/2 mt-[5%] h-[70%]">
      <div class="max-w-4xl p-4 bg-white shadow-md sm:p-6">
        <form class="flex flex-col gap-6 pt-10">

          <!-- Column 1: 3 dropdowns -->
          <div class="flex flex-col gap-4 sm:flex-row">
            <div class="flex flex-col flex-1">
              <label class="text-gray-700 font-extralight ">Location</label>
              <select class="p-2 transition duration-300 transform border border-gray-300 focus:outline-none focus:ring-1 focus:ring-black">
                <option value=""></option>
                <option value="1">Option 1</option>
                <option value="2">Option 2</option>
                <option value="3">Option 3</option>
              </select>
            </div>
            <div class="flex flex-col flex-1">
              <label class="text-gray-700 font-extralight">Type</label>
              <select class="p-2 transition duration-300 transform border border-gray-300 focus:outline-none focus:ring-1 focus:ring-black">
                <option value=""></option>
                <option value="1">Option 1</option>
                <option value="2">Option 2</option>
                <option value="3">Option 3</option>
              </select>
            </div>
            <div class="flex flex-col flex-1">
              <label class="text-gray-700 font-extralight">Sort By</label>
              <select class="p-2 transition duration-300 transform border border-gray-300 focus:outline-none focus:ring-1 focus:ring-black">
                <option value=""></option>
                <option value="1">Option 1</option>
                <option value="2">Option 2</option>
                <option value="3">Option 3</option>
              </select>
            </div>
          </div>

          <!-- Column 2: 2 dropdowns + 2 textboxes -->
          <div class="flex flex-col gap-4 sm:flex-row">
            <div class="flex flex-col flex-1">
              <label class="text-gray-700 font-extralight">Bedrooms</label>
              <select class="p-2 transition duration-300 transform border border-gray-300 focus:outline-none focus:ring-1 focus:ring-black">
                <option value=""></option>
                <option value="1">Option 1</option>
                <option value="2">Option 2</option>
                <option value="3">Option 3</option>
              </select>
            </div>
            <div class="flex flex-col flex-1">
              <label class="text-gray-700 font-extralight">Baths</label>
              <select class="p-2 transition duration-300 transform border border-gray-300 focus:outline-none focus:ring-1 focus:ring-black">
                <option value=""></option>
                <option value="1">Option 1</option>
                <option value="2">Option 2</option>
                <option value="3">Option 3</option>
              </select>
            </div>
            <div class="flex flex-col flex-1">
              <label class="text-gray-700 font-extralight">Min Price</label>
              <input type="text" placeholder="" class="p-2 duration-300 border-b border-gray-300 focus:outline-none focus:ring-1 focus:ring-black">
            </div>
            <div class="flex flex-col flex-1">
              <label class="text-gray-700 font-extralight">Max Price</label>
              <input type="text" placeholder="" class="p-2 transition duration-300 transform border-b border-gray-300 focus:outline-none focus:ring-1 focus:ring-black">
            </div>
          </div>

          <!-- Submit Button -->
          <div class="text-right">
            <button type="submit" class="px-6 py-2 text-black transition duration-300 transform outline-1 hover:bg-gray-700 hover:text-white">
              Search
            </button>
          </div>

        </form>
      </div>
    </div>
  </div>

  <div class="bg-gray-100 mt-30">
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
