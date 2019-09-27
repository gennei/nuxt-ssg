<template>
  <div class="container">
    <Header></Header>
    <div id="A" class="section">A</div>
    <div id="B" class="section">B</div>
    <div id="C" class="section">C</div>
    <div id="D" class="section">D</div>
    <Footer></Footer>
  </div>
</template>

<script>
import AppLogo from "~/components/atom/AppLogo.vue";

import Header from "~/components/molecules/Header.vue";
import Footer from "~/components/molecules/Footer.vue";

export default {
  components: {
    AppLogo,
    Header,
    Footer
  }
};
</script>

<style>
.container {
  height: 100%;
}
.section {
  width: 100%;
  height: 400px;
  line-height: 400px;
  text-align: center;
}
#A {
  background-color: red;
}
#B {
  background-color: blue;
}
#C {
  background-color: green;
}
#D {
  background-color: purple;
}
</style>

