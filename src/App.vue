<template>
  <Navbar />
  <router-view />
  <Footer />
</template>

<style>
@import url("https://fonts.googleapis.com/css2?family=Montserrat&family=Poppins&display=swap");
* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
  font-family: "Poppins", sans-serif;
}
:root {
  --button-back-active: #ff8f00;
  --button-back: rgb(247, 204, 149);
}
</style>

<script>
import Navbar from "./components/Navbar";
import Footer from "./components/Footer";
export default {
  components: {
    Navbar,
    Footer,
  },
};
</script>