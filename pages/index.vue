<template>
  <div class="global-container">
    <heading></heading>
    <profile></profile>
    <skills />
  </div>
</template>

<script>
import "normalize.css";
import Footer from "~/components/organisms/Footer.vue";
import Heading from "~/components/organisms/Heading.vue";
import Skills from "~/components/organisms/Skills.vue";
import Profile from "~/components/organisms/Profile.vue";

export default {
  components: {
    Footer,
    Heading,
    Skills,
    Profile
  }
};
</script>

<style>
body {
  font-size: 20px;
  color: #5a5a5a;
  font-family: monospace;
  background-color: #f2f2f2;
}
</style>
<style scoped>
.global-container {
  height: 100%;
}
</style>

