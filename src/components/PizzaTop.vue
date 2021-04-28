<template>
  <div class="p-top">
    <h1>Browse Our Extensive Range Of Pizzas</h1>
    <a href="#pizzas"><button>Browse Now</button></a>
  </div>
</template>

<script>
export default {};
</script>

<style scoped>
.p-top {
  width: 90%;
  margin: auto;
  display: flex;
  align-items: center;
  text-align: center;
  justify-content: center;
  margin: 3rem auto;
  flex-direction: column;
  height: fit-content;
}
.p-top > button {
  margin: 2rem 0rem;
}
.p-top > h1 {
  padding-bottom: 1.3rem;
}
</style>