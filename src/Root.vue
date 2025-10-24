<script setup>
import Layout from './layouts/Layout.vue'
import Home from './Home.vue'
import About from './About.vue'
import BuyersGuide from './BuyersGuide.vue'
import SearchListings from './SearchListings.vue'
import Carousel from './Carousel.vue'
import LogoScroll from './LogoScroll.vue'
import Services from './Services.vue'
import Contact from './Contact.vue'
import Location from './Location.vue'
</script>
<template>
<Layout>
    <main class="mt-0">
        <section id="Home" class="relative min-h-screen py-8 mx-auto"><Home /> </section>
        <section id="About" class="min-h-screen pt-0"><About /> </section>
        <section id="BuyersGuide" class="min-h-screen pt-0"><BuyersGuide /> </section>
        <section id="SearchListings" class="min-h-screen pt-0"><SearchListings /> </section>
        <section id="LogoScroll" class="pt-0 pb-20"><LogoScroll /> </section>
        <section id="Carousel" class="py-15 pb-20 bg-black/90 "><Carousel /> </section>
        <section id="Services" class="min-h-screen pt-0"><Services /> </section>
        <section id="Contact" class="min-h-screen pt-0"><Contact /> </section>
        <section id="Location" class="min-h-screen pt-0"><Location /> </section>
    </main>
</Layout>
</template>