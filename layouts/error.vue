<template>
  <div class="container">
    <main>
      <h1 v-if="error.statusCode === 404">
        Custom error page - Page not found
      </h1>
      <img v-if="error.statusCode === 404" src="@/assets/404.gif" />
      <h1 v-else>An error occurred</h1>
      <NuxtLink to="/">Home page</NuxtLink>
    </main>
  </div>
</template>

<script>
export default {
  props: ["error"],
  layout: "blog", // you can set a custom layout for the error page
};
</script>
