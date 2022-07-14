<template>
  <header>
    <h3 class="logo">Nuxt website</h3>
    <ul>
      <li><nuxt-link to="/">Home</nuxt-link></li>
      <li><nuxt-link to="/about">About</nuxt-link></li>
      <li><nuxt-link to="/contact">Contact</nuxt-link></li>
      <li><nuxt-link to="/donate">Donate</nuxt-link></li>
    </ul>
  </header>
</template>

<style scoped>
header {
  background-color: #92d1c3;
  color: white;
  width: 100%;
  height: 8rem;
  display: flex;
  justify-content: space-between;
  box-sizing: border-box;
  margin: 0;
  padding: 0 5rem;
  align-items: center;
}

h3.logo {
  font-size: 3rem;
  font-weight: 400;
}

ul {
  padding: 0;
  margin: 0;
  list-style-type: none;
  display: flex;
}

li {
  font-size: 1.25rem;
}

li a {
  padding: 1rem 0.5rem;
  color: inherit;
  text-decoration: none;
}
</style>
