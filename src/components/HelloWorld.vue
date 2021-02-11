<template>
  <div class="hello">
    <div class="jumbotron container">
      <i class="fab icon fa-vuejs"></i>
      <i class="fab icon fa-angular"></i>
      <i class="fab icon fa-mdb"></i>
      <i class="fab icon fa-npm"></i>
    </div>
    <br />
    <h1>{{ msg }}</h1>
    <p itemscope itemid="author">
      For a guide and to see some templates, email me I will be happy to provide
      <br />
      some. I understand you want your site to look great, and I want to be sure
      <br />
      how I can help you.
      <a href="mailto:stephenbrooks714@gmail.com">Message Us</a>
    </p>
    <br /><br /><br />
    <div class="container" itemtype="app plugins">
      <div class="row content-bg">
        <div class="col-md-4">
          <h3>
            <i class="fas fa-puzzle-piece"></i> <br />
            Installed CLI Plugins
          </h3>
          <ul>
            <li>
              <a
                href="https://github.com/vuejs/vue-cli/tree/dev/packages/%40vue/cli-plugin-babel"
                target="_blank"
                rel="noopener"
                >babel</a
              >
            </li>
            <li>
              <a
                href="https://github.com/vuejs/vue-cli/tree/dev/packages/%40vue/cli-plugin-pwa"
                target="_blank"
                rel="noopener"
                >pwa</a
              >
            </li>
            <li>
              <a
                href="https://github.com/vuejs/vue-cli/tree/dev/packages/%40vue/cli-plugin-router"
                target="_blank"
                rel="noopener"
                >router</a
              >
            </li>
            <li>
              <a
                href="https://github.com/vuejs/vue-cli/tree/dev/packages/%40vue/cli-plugin-vuex"
                target="_blank"
                rel="noopener"
                >vuex</a
              >
            </li>
            <li>
              <a
                href="https://github.com/vuejs/vue-cli/tree/dev/packages/%40vue/cli-plugin-eslint"
                target="_blank"
                rel="noopener"
                >eslint</a
              >
            </li>
            <li>
              <a
                href="https://github.com/vuejs/vue-cli/tree/dev/packages/%40vue/cli-plugin-typescript"
                target="_blank"
                rel="noopener"
                >typescript</a
              >
            </li>
          </ul>
        </div>
        <div class="col-md-4">
          <h3>
            <i class="fas fa-link"></i> <br />
            Essential Links
          </h3>
          <ul>
            <li>
              <a href="https://vuejs.org" target="_blank" rel="noopener"
                >Core Docs</a
              >
            </li>
            <li>
              <a href="https://forum.vuejs.org" target="_blank" rel="noopener"
                >Forum</a
              >
            </li>
            <li>
              <a href="https://chat.vuejs.org" target="_blank" rel="noopener"
                >Community Chat</a
              >
            </li>
            <li>
              <a href="https://twitter.com/vuejs" target="_blank" rel="noopener"
                >Twitter</a
              >
            </li>
            <li>
              <a href="https://news.vuejs.org" target="_blank" rel="noopener"
                >News</a
              >
            </li>
          </ul>
        </div>
        <div class="col-md-4">
          <h3>
            <i class="fas fa-globe"></i> <br />
            Ecosystem
          </h3>
          <ul>
            <li>
              <a href="https://router.vuejs.org" target="_blank" rel="noopener"
                >vue-router</a
              >
            </li>
            <li>
              <a href="https://vuex.vuejs.org" target="_blank" rel="noopener"
                >vuex</a
              >
            </li>
            <li>
              <a
                href="https://github.com/vuejs/vue-devtools#vue-devtools"
                target="_blank"
                rel="noopener"
                >vue-devtools</a
              >
            </li>
            <li>
              <a
                href="https://vue-loader.vuejs.org"
                target="_blank"
                rel="noopener"
                >vue-loader</a
              >
            </li>
            <li>
              <a
                href="https://github.com/vuejs/awesome-vue"
                target="_blank"
                rel="noopener"
                >awesome-vue</a
              >
            </li>
          </ul>
        </div>
      </div>
    </div>
    <br /><br /><br /><br />
    <div class="jumbotron">
      <h1 class="display-4">Languages Used for Build</h1>
      <ul>
        <li>Vue.js</li>
        <li>TypeScript</li>
        <li>SCSS</li>
        <li>HTML</li>
        <li>css</li>
        <li>node</li>
        <li>Babel</li>
        <li>MDB5</li>
      </ul>
      <br />
      <div class="row" itemid="article">
        <div class="col-md-4">
          <b>HTML</b> is the frame and language that the web browsers read and
          also the most basic one to learn. It lays out content and helps with
          form submissions, so it does has some powerful tags that are used in
          all apps.
        </div>
        <div class="col-md-4">
          <b>CSS & SCSS</b> are for styling what you see and making the pages
          responsive. From giving content color; changins font sizes, making
          images appears where ever you want them too. The flexbility from most
          frameworks still rely on css.
        </div>
        <div class="col-md-4">
          <b>Vue & TypeScript</b> are the frameworks we'll be using for the
          majority of the courses. A few will be with
          <em>asp.Net Core</em> using C#, but in reality the language or
          framework you use depends on the client, employer, or even the project
          type.
        </div>
      </div>
    </div>
  </div>
</template>

<script lang="ts">
import { Options, Vue } from "vue-class-component";

@Options({
  props: {
    msg: String
  }
})
export default class HelloWorld extends Vue {
  msg!: string;
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped lang="scss">
h3 {
  margin: 40px 0 0;
}
ul {
  list-style-type: none;
  padding: 0;
}
li {
  display: inline-block;
  margin: 0 10px;
}
a {
  color: #42b983;
}
.icon {
  font-size: 36px;
  color: grey;
  letter-spacing: 24px;
}
.content-bg {
  background: url(https://i.stack.imgur.com/dWIW2.jpg) no-repeat center center
    fixed;
  -webkit-background-size: cover;
  -moz-background-size: cover;
  -o-background-size: cover;
  background-size: cover;
  width: 100%;
  height: auto;
  padding-top: 30px;
  padding-bottom: 30px;
}
</style>
