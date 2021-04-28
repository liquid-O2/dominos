<template>
  <section>
    <div class="title">
      <i class="fas fa-dollar-sign"> </i>
      <span> Pizzas On Sale Now</span>
    </div>
    <div class="sectiontwo" id="pizzas">
      <!-- CARDS -->
      <div class="card">
        <div class="image">
          <img src="./deluxe-pizza-2.png" alt="" />
        </div>
        <div class="details">
          <span class="this">Pepperoni Pizza</span>
          <span>$2.99</span>
        </div>
        <button>Buy Now</button>
      </div>
      <div class="card">
        <div class="image">
          <img src="./mushroom.png" alt="" />
        </div>
        <div class="details">
          <span class="this">Mushroom Pizza</span>
          <span>$3.99</span>
        </div>

        <button>Buy Now</button>
      </div>
      <div class="card">
        <div class="image">
          <img src="./cheese.png" alt="" />
        </div>
        <div class="details">
          <span class="this">Cheese Pizza</span>
          <span>$1.99</span>
        </div>

        <button>Buy Now</button>
      </div>
    </div>
  </section>
</template>

<script>
export default {};
</script>

<style scoped>
section {
  width: 90%;
  margin: auto;
}
.sectiontwo {
  width: 90%;
  margin: auto;
  display: flex;

  height: fit-content;
}
.card {
  background-color: #f6f4f1;
  border-radius: 1rem;
  width: 30rem;
  height: fit-content;
  display: flex;
  flex-direction: column;
  margin: 2rem 1rem;
}
.image {
  width: 100%;
  height: 20rem;
}
img {
  max-width: 100%;
  max-height: 100%;
  object-fit: contain;
}
.details {
  display: flex;
  justify-content: space-between;
  padding: 1rem;
  text-align: center;
}
button {
  width: 50%;
  margin: 1rem auto;
}

.details > span {
  color: crimson;
  font-weight: bold;
  font-size: 1.2rem;
}
.details > .this {
  color: black;
}
.title {
  font-size: 1.3rem;
  font-weight: bold;
  padding: 1rem 0rem;
}

@media screen and (max-width: 863px) {
  .sectiontwo {
    flex-wrap: wrap;
  }
}
</style>