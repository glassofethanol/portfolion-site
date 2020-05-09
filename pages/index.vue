<template>
  <div class="container">
    <div>
      <h1 class="title rainbow-text-static">Ethân ap Paul</h1>
      <h2 class="subtitle rainbow-text-static">Web Developer</h2>
      <Tools />
    </div>
  </div>
</template>

<script>
import Vue from "vue";
import axios from "axios";
import Tools from "../components/tools.vue";
import About from "../components/about.vue";

export default {
  components: {
    About,
    Tools
  }
};
</script>

<style>
@import url("https://fonts.googleapis.com/css2?family=Roboto:wght@700&display=swap");
:root {
  --red: #ca4246;
  --orange: #e16541;
  --yellow: #f18f43;
  --green: #8b9862;
  --blue: #476098;
  --purple: #a7489b;

  --body-background-color: #fff;
  --text-color: #5a24c2;
  --text-color-transparent: rgba(90, 36, 195, 0.2);
  --text-color-blocks: #401593;
  --text-color-tags: #270667;

  --main-text-width: 666px;
  --main-text-width-wide: 900px;
  --main-container-padding: 117px;

  --code-block-bg: #ece3e1;

  --text-size-base: 24px;
  --text-size-xlarge: 5.2rem;
  --text-size-default: 1rem;
  --text-size-large: 1.5rem;
  --text-size-small: 0.75rem;
  --text-size-xsmall: 0.58rem;
  --text-size-medium: 1.25rem;

  --color-post-2: #f3cfcd;
  --color-post-3: #ede389;
  --color-post-1: #c7eeec;
  --color-post-4: #cce6c9;
}

@media screen and (max-width: 750px) {
  :root {
    --text-size-base: 20px;
    --text-size-small: 0.9rem;
    --text-size-xsmall: 0.75rem;
    --text-size-xlarge: 3rem;
  }
}
html {
  overflow-x: hidden;
}

.rainbow-text-static,
#front main h1 {
  right: -250px;
  font-weight: bold;
  font-size: 125px;
  font-size: var(--text-size-xlarge);
  line-height: 130px;
  line-height: calc(var(--text-size-xlarge) + 5px);
  font-weight: 700;
  width: 600px;
  background-size: 580px;
  background: linear-gradient(
    60deg,
    var(--red) 15%,
    var(--orange) 15%,
    var(--orange) 30%,
    var(--yellow) 30%,
    var(--yellow) 45%,
    var(--green) 45%,
    var(--green) 60%,
    var(--blue) 60%,
    var(--blue) 75%,
    var(--purple) 75%
  );

  -webkit-background-clip: text;
  -webkit-text-fill-color: transparent;
}

.container {
  font-family: Roboto;

  min-height: 100vh;
  display: flex;
  justify-content: center;
  align-items: center;
  text-align: center;
}

.title {
  display: block;
  font-size: 100px;
  color: #35495e;
  letter-spacing: 1px;
}

.subtitle {
  font-weight: bold;
  font-size: 42px;
  color: #526488;
  word-spacing: 5px;
  padding-bottom: 15px;
}

.links {
  padding-top: 15px;
}
</style>
