<template>
  <nav>
    <div class="navigation">
      <i class="fas fa-pizza-slice"> <span> Dominos</span></i>
      <div class="links">
        <router-link class="item1" :to="{ name: 'Home' }">Home</router-link>
        <router-link class="item2" :to="{ name: 'Pizzas' }">Pizzas</router-link>
      </div>
    </div>
  </nav>
</template>

<script>
export default {};
</script>

<style scoped>
nav {
  padding: 0.5rem 0rem;
  box-shadow: 0px 24px 80px 3px rgba(0, 0, 0, 0.14),
    0px 9px 600px 8px rgba(0, 0, 0, 0.12),
    0px 11px 600px -7px rgba(0, 0, 0, 0.2);
  width: 100vw;
  height: 8vh;
}
.navigation {
  display: flex;
  width: 90%;
  margin: auto;
}
.navigation > i {
  flex: 4 1 30rem;
}
.links {
  display: flex;
}
.links > a {
  background: var(--button-back);
  padding: 0.6rem;
  border-radius: 0.7rem;
  text-decoration: none;
  color: black;
  font-size: 1rem;
  margin: 0rem 0.5rem;
  box-shadow: 0px 24px 80px 1px rgb(247, 204, 149),
    0px 9px 600px 3px rgba(0, 0, 0, 0.12),
    0px 11px 600px -3px rgba(0, 0, 0, 0.2);
}
i {
  font-size: 1rem;
  padding-top: 1rem;
  padding-right: 3rem;
}
i > span {
  font-size: 1.1rem;
}

.links > a.router-link-exact-active {
  background: var(--button-back-active);
  color: white;
  box-shadow: 0px 24px 90px 1px #fbb34d, 0px 9px 600px 2px #fbb34d,
    0px 11px 600px -1px #fbb34d;
}
a > i {
  font-size: 1.1rem;
  padding: 0rem;
}
#t {
  padding: 0rem;
  padding-top: 0.7rem;

  padding-left: 0.5rem;
  padding-right: 0.5rem;
}
span {
  padding-left: 0.3rem;
}
</style>