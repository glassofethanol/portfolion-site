<template>
  <div class="container">
    <div>
      <h1 class="title-blog rainbow-text-static">Projects</h1>
    </div>
    <ProjectCards />
  </div>
</template>

<script>
import Vue from "vue";
import ProjectCards from "../components/projectcards.vue";

export default {
  components: {
    ProjectCards
  }
};
</script>

<style>
html {
  overflow-x: hidden;
}
</style>
