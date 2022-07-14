<template>
  <div>
    <Header></Header>
    <nuxt />
  </div>
</template>

<script>
import Header from "./partials/Header.vue";

export default {
  loading: true,
  components: { Header },
  head: {
    link: [
      {
        rel: "stylesheet",
        href: "https://fonts.googleapis.com/css2?family=Lato&display=swap",
      },
    ],
  },
};
</script>

<style>
html,
body {
  font-family: "Lato", sans-serif;
  margin: 0;
  padding: 0;
  width: 100vw;
}

.container {
  width: 90%;
  margin: 0 auto;
}

main {
  width: 100%;
  display: flex;
  flex-direction: column;
  align-items: center;
}

p {
  text-indent: 3em;
  font-size: 1.25rem;
  line-height: 1.5;
  margin-top: 1rem;
}

h1 {
  font-size: 3rem;
}
</style>
