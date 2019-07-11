<template>
  <section>
    <h1>About Me</h1>
    <h2 class="subheading">自己紹介</h2>
    <div class="profile">
      <ul>
        <li>門倉 央 | Hiroshi Kadokura</li>
        <li>神奈川県相模原市在住</li>
        <li>レイクランド大学ジャパンキャンパス卒</li>
        <li>前職 ( ~ 2019/4) は女性向けヘアアクセサリーの営業</li>
        <li>英語 可</li>
      </ul>
    </div>
    <div class="profile profile-detail">
      <ul>
        <li>
          <a href="https://github.com/Abbiscuit">GitHub</a>
        </li>
        <li>
          <a href="https://twitter.com/hiro_dev_hnyka">Twitter</a>
        </li>
        <li>
          <a href="https://qiita.com/Abbiscuit">Qiita</a>
        </li>
      </ul>
    </div>
    <h2 class="subheading">学習歴</h2>
    <p>これまでに学習した内容は以下の通りです。</p>
    <ul>
      <li>HTML/ CSS</li>
      <ul>
        <li>Flexbox</li>
        <li>BEM設計</li>
      </ul>
      <li>JavaScript</li>
      <ul>
        <li>ES5</li>
        <li>ES6</li>
        <li>async/awaitほか</li>
        <li>TypeScript</li>
      </ul>
      <li>React, Redux</li>
      <ul>
        <li>react-router</li>
        <li>React Hooks</li>
        <li>React Context API</li>
        <li>react-router</li>
        <li>Reactのパフォーマンス</li>
        <li>Progressive Web App</li>
      </ul>
      <li>Vue & Nuxt（少々）</li>
      <li>Node.js & Express</li>
      <li>MongoDB, PostgreSQL</li>
      <li>Google Firebase</li>
      <li>Sketch App</li>
    </ul>
    <p>フロントエンド、バックエンドともに対応可能な言語であり、またSPAなどのモダンな技術に興味があったので、2019/4よりJavaScriptを集中的に学んできました。</p>
  </section>
</template>

<script>
export default {
  components: {},
  head() {
    return {
      title: "About | Portfolio",
      meta: [
        { name: "description", content: "ポートフォリオです" },
        { name: "keywords", content: "portfolio, nuxt, ポートフォリオ" }
      ]
    };
  }
};
</script>

<style scope>
.profile {
  width: 100%;
  margin: 0 auto;
}

.profile ul {
  padding: 0;
  list-style: none;
}

.profile li {
  padding: 10px 0;
}
</style>
