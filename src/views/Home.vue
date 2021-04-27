<template>
  <Hero />

  <Sale />

  <AboutUs />
  <Footer />
</template>

<script>
// @ is an alias to /src
import Sale from "../components/Sale.vue";
import Hero from "../components/Hero.vue";
import AboutUs from "../components/AboutUs.vue";
import Footer from "../components/Footer.vue";
export default {
  name: "Home",
  components: {
    Sale,
    Hero,
    AboutUs,
    Footer,
  },
};
</script>
<style>
/* SECOND SECTION */
</style>