<template>
  <Navbar />
  <router-view />
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

export default {
  components: {
    Navbar,
  },
};
</script>