<script setup>


</script>
<template>
    <div class="relative ">
        <header class="fixed top-0 left-0 z-50 w-full bg-white">
            <nav class="flex items-center justify-between p-0 mx-auto text-sm text-center text-black pr-25">
                <div class="pt-0 ">
                    <a href="#Home"><img src="/images/logo.png"
                    class="block mx-auto max-w-[250px] md:max-w-[350px] h-auto pl-10 md:pl-20"></a>
                </div>
                <div class="pb-3 m-0 space-x-20 text-black">
                    <a href="#Home" class="navBttn">HOME</a>
                    <a href="#About" class="navBttn">ABOUT</a>
                    <a href="" class="navBttn">CONTACT US</a>
                    <a href="" class="navBttn">MENU</a>
                </div>
            </nav>
        </header>
    </div>

    <main class="">
        <slot />
    </main>
</template>