<template>
  <div>
    <h2 class="para-text">
      I'm a software developer from South Wales, UK. Working with Functional
      Programming and Compilers. I use {{ tools }}
    </h2>
  </div>
</template>

<style scoped>
.para-text {
  padding-top: 50px;
  font-weight: bold;
  font-size: 30px;
  color: #5a24c2;
}

.para-text-other {
  padding-top: 50px;
  font-weight: bold;
  font-size: 30px;
  color: #5a24c2;
}
</style>

<script>
import Vue from "vue";
export default {
  props: {
    tools: {
      type: String,
      required: true,
    },
    required: true,
  },

  setup() {},
};
</script>
