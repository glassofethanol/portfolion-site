<template>
  <div>
    <header>
      <div class="header">
        <nuxt-link to="/">About</nuxt-link>
        <nuxt-link to="/blog">Blog</nuxt-link>
        <a href="https://www.github.com/glassofethanol">Github</a>
        <nuxt-link to="/projects">Projects</nuxt-link>
      </div>
    </header>
    <nuxt />
  </div>
</template>

<script>
import "circular-std";
import Vue from "vue";

export default {
  head() {
    return {
      title: "Ethân ap Paul",
      meta: [
        {
          hid: "Description",
          name: "Description",
          content: "Custom Description"
        }
      ]
    };
  }
};
</script>

<style>
html {
  font-family: "CircularStd";
  font-size: 16px;
  word-spacing: 1px;
  -ms-text-size-adjust: 100%;
  -webkit-text-size-adjust: 100%;
  -moz-osx-font-smoothing: grayscale;
  -webkit-font-smoothing: antialiased;
  box-sizing: border-box;
}

.header {
  text-decoration: none;
  position: relative;
  top: 30px;
  left: 70%;
  color: #5a24c2;
  word-spacing: 20px;
  font-weight: bold;
}
</style>
