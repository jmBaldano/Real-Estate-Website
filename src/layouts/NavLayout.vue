<script setup>


</script>
<template>
    <div class="relative inset-0">
        <header class="bg-amber-100 opacity-0">
            
            <nav class="flex items-center justify-between p-5 mx-auto">
                <div>
                    <a href="">logo</a>
                </div>
                <div class="space-x-5">
                    <a href="">Home</a>
                    <a href="">Services</a>
                </div>
            </nav>
        </header>
    </div>

    <main class="p-10">
        <slot />
    </main>
</template>