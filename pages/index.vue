<template>
  <section>
    <h1>
      Welcome to the portfolio of
      <span>Hiro</span>
    </h1>
    <p class="subheading">I'm into Front-end Web development now!</p>
    <p class="content">
      Hiroです！
      <br />現在、フロントエンドエンジニアとしての転職を目指しプログラミング学習をしています。
      <br />おもにJavaScriptやReactに力を入れています。
    </p>
    <p>
      <nuxt-link to="/about">自己紹介</nuxt-link>
    </p>
    <p>
      <nuxt-link to="/portfolio">ポートフォリオはこちら</nuxt-link>
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

/* span {
  display: inline;
  background: rgb(252, 101, 81);
  padding: 3px;
  font-family: "Sacramento";
} */
</style>
