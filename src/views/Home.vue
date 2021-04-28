<template>
  <Hero />

  <Sale />

  <AboutUs />
</template>

<script>
// @ is an alias to /src
import Sale from "../components/Sale.vue";
import Hero from "../components/Hero.vue";
import AboutUs from "../components/AboutUs.vue";

export default {
  name: "Home",
  components: {
    Sale,
    Hero,
    AboutUs,
  },
};
</script>
<style>
/* SECOND SECTION */
</style>