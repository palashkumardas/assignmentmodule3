<script setup>
import Footer from './components/Footer.vue'
import Contact from './components/Contact.vue'
import Faq from './components/Faq.vue'
import Price from './components/Price.vue'
import Testimonials from './components/Testimonials.vue'
import Details from './components/Details.vue';
import Hero from './components/Hero.vue';
import Header from './components/Header.vue';
import Feature from './components/Feature.vue';

</script>

<template>
  <Header></Header>
  <Hero></Hero>
  <main id="main">
    <Feature></Feature>
    <Details></Details>
    <Price></Price>
    <Testimonials></Testimonials>
    <Faq></Faq>
    <Contact></Contact>
    <Footer></Footer>
  </main>
</template>

<style scoped>

</style>
