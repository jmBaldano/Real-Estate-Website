<template>
    <a href="#Home"><img src="/images/logo1.png" class="block mx-auto max-w-[250px] md:max-w-[350px] h-auto md:pl-0 pb-10"></a>
    <h1 class="pb-10 font-serif text-2xl md:text-5xl text-center text-white">PHOTO GALLERY</h1>
    <div id="indicators-carousel" class="relative mx-auto w-full max-w-[1200px]" data-carousel="slide">
    <!-- Carousel wrapper -->
    <div class="relative md:w-full w-full max-w-[1200px] h-56 mx-auto overflow-hidden md:h-[400px]">
         <!-- Item 1 -->
        <div class="hidden duration-700 ease-in-out" data-carousel-item="active">
            <img src="/images/carousel1.png" class="absolute block w-full -translate-x-1/2 -translate-y-1/2 top-1/2 left-1/2" alt="...">
        </div>
        <!-- Item 2 -->
        <div class="hidden duration-700 ease-in-out" data-carousel-item>
            <img src="/images/carousel2.png" class="absolute block w-full -translate-x-1/2 -translate-y-1/2 top-1/2 left-1/2" alt="...">
        </div>
        <!-- Item 3 -->
        <div class="hidden duration-700 ease-in-out" data-carousel-item>
            <img src="/images/carousel3.jpg" class="absolute block w-full -translate-x-1/2 -translate-y-1/2 top-1/2 left-1/2" alt="...">
        </div>
        <!-- Item 4 -->
        <div class="hidden duration-700 ease-in-out" data-carousel-item>
            <img src="/images/carousel4.png" class="absolute block w-full -translate-x-1/2 -translate-y-1/2 top-1/2 left-1/2" alt="...">
        </div>
        <!-- Item 5 -->
        <div class="hidden duration-700 ease-in-out" data-carousel-item>
            <img src="/images/carousel5.png" class="absolute block w-full -translate-x-1/2 -translate-y-1/2 top-1/2 left-1/2" alt="...">
        </div>
        <div class="hidden duration-700 ease-in-out" data-carousel-item>
            <img src="/images/carousel6.png" class="absolute block w-full -translate-x-1/2 -translate-y-1/2 top-1/2 left-1/2" alt="...">
        </div>
        <div class="hidden duration-700 ease-in-out" data-carousel-item>
            <img src="/images/carousel7.png" class="absolute block w-full -translate-x-1/2 -translate-y-1/2 top-1/2 left-1/2" alt="...">
        </div>
    </div>
    <!-- Slider indicators -->
    <div class="absolute z-30 flex space-x-3 -translate-x-1/2 md:top-103 bottom-6 left-1/2 ">
    <button type="button" class="relative w-12 h-12 overflow-hidden cursor-pointer" aria-current="true" aria-label="Slide 1" data-carousel-slide-to="0">
        <img src="/images/carousel1.png" class="object-cover w-full h-full ">
         <div class="absolute inset-0 bg-black/50 hover:bg-black/10 overlay"></div>
    </button>
    <button type="button" class="relative w-12 h-12 overflow-hidden cursor-pointer" aria-current="false" aria-label="Slide 2" data-carousel-slide-to="1">
        <img src="/images/carousel2.png" class="object-cover w-full h-full ">
            <div class="absolute inset-0 bg-black/50 hover:bg-black/10 overlay"></div>
    </button>
    <button type="button" class="relative w-12 h-12 overflow-hidden cursor-pointer" aria-current="false" aria-label="Slide 3" data-carousel-slide-to="2">
        <img src="/images/carousel3.jpg" class="object-cover w-full h-full ">
            <div class="absolute inset-0 bg-black/50 hover:bg-black/10 overlay"></div>
    </button>
    <button type="button" class="relative w-12 h-12 overflow-hiddencursor-pointer" aria-current="false" aria-label="Slide 4" data-carousel-slide-to="3">
        <img src="/images/carousel4.png" class="object-cover w-full h-full">
            <div class="absolute inset-0 bg-black/50 hover:bg-black/10 overlay"></div>
    </button>
    <button type="button" class="relative w-12 h-12 overflow-hiddencursor-pointer" aria-current="false" aria-label="Slide 5" data-carousel-slide-to="4">
        <img src="/images/carousel5.png" class="object-cover w-full h-full">
            <div class="absolute inset-0 bg-black/50 hover:bg-black/10 overlay"></div>
    </button>
    <button type="button" class="relative w-12 h-12 overflow-hiddencursor-pointer" aria-current="false" aria-label="Slide 6" data-carousel-slide-to="5">
        <img src="/images/carousel6.png" class="object-cover w-full h-full">
            <div class="absolute inset-0 bg-black/50 hover:bg-black/10 overlay"></div>
    </button>
    <button type="button" class="relative w-12 h-12 overflow-hidden cursor-pointer" aria-current="false" aria-label="Slide 7" data-carousel-slide-to="6">
        <img src="/images/carousel7.png" class="object-cover w-full h-full " >
            <div class="absolute inset-0 bg-black/50 hover:bg-black/10 overlay"></div>
    </button>
</div>
    <!-- Slider controls -->
    <button type="button" class="absolute top-0 z-30 flex items-center justify-center h-full px-4 cursor-pointer hover:bg-black/20 start-0 group focus:outline-none" data-carousel-prev>
        <span class="inline-flex items-center justify-center w-10 h-10  group-focus:ring-white group-focus:outline-none">
            <svg class="w-4 h-4 text-white dark:text-gray-800 rtl:rotate-180" aria-hidden="true" xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 6 10">
                <path stroke="currentColor" stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M5 1 1 5l4 4"/>
            </svg>
            <span class="sr-only">Previous</span>
        </span>
    </button>
    <button type="button" class="absolute top-0 z-30 flex items-center justify-center h-full px-4 cursor-pointer hover:bg-black/20 end-0 group focus:outline-none" data-carousel-next>
        <span class="inline-flex items-center justify-center w-10 h-10   dark:group-focus:ring-white group-focus:outline-none">
            <svg class="w-4 h-4 text-white dark:text-gray-800 rtl:rotate-180" aria-hidden="true" xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 6 10">
                <path stroke="currentColor" stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="m1 9 4-4-4-4"/>
            </svg>
            <span class="sr-only">Next</span>
        </span>
    </button>
</div>

</template>

