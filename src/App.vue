<script setup>
import Hero from './components/Hero.vue';
import Navbar from './components/Navbar.vue';
import EventGrid from './components/EventGrid.vue';
import Sphere from './components/Sphere.vue';
import ProjectGrid from './components/ProjectGrid.vue';
import MembersGrid from './components/MembersGrid.vue';
import Footer from './components/Footer.vue';
</script>

<template>
    <Navbar />
    <Sphere />
    <Hero />
    <EventGrid />
    <ProjectGrid />
    <MembersGrid/>
    <Footer/>
</template>

<style lang="postcss">
a {
    @apply cursor-pointer;
}

</style>