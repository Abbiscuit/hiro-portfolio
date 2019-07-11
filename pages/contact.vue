<template>
  <section>
    <h1>Contact</h1>
    <p class="subheading">ご連絡について</p>
    <p>ご興味を持っていただけましたら、ぜひご連絡をお願いします！！</p>
    <p>Twtter DM</p>
    <p class="email">litm.yolo@gmail.com</p>
  </section>
</template>

<script>
export default {
  components: {},
  head() {
    return {
      title: "Contact | Portfolio",
      meta: [
        { name: "description", content: "ポートフォリオです" },
        { name: "keywords", content: "portfolio, nuxt, ポートフォリオ" }
      ]
    };
  }
};
</script>

<style scoped>
.email {
  text-decoration: underline;
}
</style>
