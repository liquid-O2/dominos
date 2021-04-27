<template>
  <div class="main">
    <div class="text">
      <h1>Enjoy Our Delicious Range Of Pizzas</h1>
      <p>
        Served Fresh Out Of The Oven, With 100% Itallian Mozzerella And Fresh
        Herbs
        <br />
        <span>Best Pizza In The World. Have You Tasted Better?</span>
      </p>

      <router-link :to="{ name: 'Pizzas' }"
        ><button>Browse Now</button></router-link
      >
    </div>
    <div class="image">
      <img src="./cheese.png" alt="pizza" />
    </div>
  </div>
</template>

<script>
export default {};
</script>

<style>
.main {
  display: flex;
  height: 100vh;
  width: 90%;
  align-items: center;
  margin: auto;
}
img {
  height: 30rem;
  width: 30rem;
  object-fit: cover;
}
.text {
  flex: 2 1 30rem;
  font-size: 1.2rem;
}
.text h1 {
  padding-bottom: 1rem;
}
.text p {
  padding-bottom: 1.3rem;
}
span {
  padding-top: 1rem;
}

button {
  padding: 1rem;
  font-size: 1.2rem;
  border: none;
  border-radius: 1rem;
  background-color: var(--button-back);
  box-shadow: 0px 24px 80px 1px rgb(247, 204, 149),
    0px 9px 600px 3px rgba(0, 0, 0, 0.12),
    0px 11px 600px -3px rgba(0, 0, 0, 0.2);
}
button:hover {
  background-color: var(--button-back-active);
  color: white;
}
@media screen and (max-width: 863px) {
  .main {
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