<template>
  <div>
    <h2 class="tools">
      My Tools of Choice
      <div>
        <vue-typer
          :text="[
            'Laravel',
            'Scala',
            'Nuxt.js',
            'Vue',
            'C#',
            'React',
            'Next.js'
          ]"
          :repeat="Infinity"
          :shuffle="false"
          :initial-action="typing"
          :pre-type-delay="70"
          :type-delay="70"
          :pre-erase-delay="1500"
          :erase-delay="250"
          erase-style="select-all"
          :erase-on-complete="true"
          caret-animation="blink"
        ></vue-typer>
      </div>
    </h2>
  </div>
</template>

<script>
import Vue from "vue";
import { VueTyper } from "vue-typer";
export default {
  components: {
    VueTyper
  }
};
</script>

<style>
.list-items {
  color: red;
}

.tools,
h1 {
  color: #5a24c2;
}
</style>
