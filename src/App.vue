<template>
  <div id="app">
    <Navbar />
    <Description />
    <Carousel />
    <Contact />
    <Footer />
  </div>
</template>

<script>
import Navbar from './components/Navbar.vue';
import Description from './components/Description.vue';
import Carousel from './components/Carousel.vue';
import Contact from './components/Contact.vue';
import Footer from './components/Footer.vue';

export default {
  components: {
    Navbar,
    Description,
    Carousel,
    Contact,
    Footer,
  },
}
</script>

<style>

</style>
