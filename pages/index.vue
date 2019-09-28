<template>
  <div class="container">
    <Header></Header>
    <heading></heading>
    <profile></profile>
    <skills></skills>
    <Footer></Footer>
  </div>
</template>

<script>
import AppLogo from "~/components/atom/AppLogo.vue";

import Header from "~/components/organisms/Header.vue";
import Footer from "~/components/organisms/Footer.vue";
import Heading from "~/components/organisms/Heading.vue";
import Skills from "~/components/organisms/Skills.vue";
import Profile from "~/components/organisms/Profile.vue";

export default {
  components: {
    AppLogo,
    Header,
    Footer,
    Heading,
    Skills,
    Profile
  }
};
</script>

<style>
.container {
  height: 100%;
}
</style>

