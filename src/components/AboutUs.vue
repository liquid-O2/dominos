<template>
  <section>
    <div class="about">
      <div class="text">
        <h1>The Worldwide Leader In Pizza Delivery</h1>
        <p>
          Founded in 1960, Domino's is the recognized world leader in pizza
          delivery operating a network of company-owned and franchise-owned
          stores in the United States and international markets. Domino's is a
          company of exceptional people on a mission to be the best pizza
          delivery company in the world.
        </p>
      </div>
      <div class="image">
        <img src="./domino.png" alt="" />
      </div>
    </div>
  </section>
</template>

<script>
export default {};
</script>

<style scoped>
section {
  margin-top: 2rem;
  background-color: #f1e1cc;
}
.about {
  width: 90%;
  margin: auto;
  display: flex;
  align-items: center;
  height: fit-content;
}
img {
  width: 25rem;
  height: 25rem;
  object-fit: contain;
}
.image {
  padding: 3rem 0rem;
  padding-left: 2rem;
  flex: 1 1 30rem;
}
.text {
  flex: 2 1 60rem;
}
@media screen and (max-width: 863px) {
  .about {
    flex-wrap: wrap;
    justify-content: center;
    text-align: center;
    height: fit-content;
  }
  .text {
    padding-top: 4rem;
  }
  button {
    margin-bottom: 1rem;
  }
}
</style>