<template>
  <section>
    <h1>Lorem ipsum dolor sit amet.</h1>
    <p class="subheading">Nuxt nuxt nuxt</p>
    <p>Lorem ipsum dolor sit amet consectetur adipisicing elit.</p>
    <p>
      <nuxt-link to="/services">ポートフォリオはこちら</nuxt-link>
    </p>
  </section>
</template>

<script>
export default {
  components: {},
  head() {
    return {
      title: "Welcome | Portfolio",
      meta: [
        { name: "description", content: "ポートフォリオです" },
        { name: "keywords", content: "portfolio, nuxt, ポートフォリオ" }
      ]
    };
  }
};
</script>

<style scoped>
a {
  color: #333;
  text-decoration: none;
  font-weight: 700;
  padding: 3px 0;
  border-bottom: 2px solid rgb(252, 101, 81);
}

a:hover {
  opacity: 0.8;
}
</style>
