<template>
  <footer>
    <h1>© All Rights And Reserved Dominos</h1>
    <div class="icons">
      <i class="fab fa-twitter"></i>
      <i class="fab fa-facebook"></i>
      <i class="fas fa-envelope"></i>
    </div>
    <h1>Designed And Built By <a href="www.github.io/liquid-o2">Arunava</a></h1>
  </footer>
</template>

<script>
export default {};
</script>

<style scoped>
footer {
  padding: 1rem 0rem;
  background-color: #e5e4e2;
  display: flex;
  flex-direction: column;
  justify-content: center;
  align-items: center;
}
h1 {
  font-size: 1.1rem;
  padding: 1rem 0rem;
}
.icons {
  display: flex;
  justify-content: space-between;
}
i {
  margin: 0rem 1rem;
  font-size: 1.5rem;
}
a {
  text-decoration: none;
  color: black;
  border-bottom: 3px solid var(--button-back);
}
</style>