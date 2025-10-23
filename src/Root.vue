<script setup>
import Layout from './layouts/Layout.vue'
import Home from './Home.vue'
import About from './About.vue'
import BuyersGuide from './BuyersGuide.vue'
import SearchListings from './SearchListings.vue'
</script>
<template>
<Layout>
    <main class="mt-0">
        <section id="Home" class="relative min-h-screen py-8 mx-auto"><Home /> </section>
        <section id="About" class="min-h-screen pt-0"><About /> </section>
        <section id="BuyersGuide" class="min-h-screen pt-0"><BuyersGuide /> </section>
        <section id="SearchListings" class="min-h-screen pt-0"><SearchListings /> </section>
    </main>
</Layout>
</template>