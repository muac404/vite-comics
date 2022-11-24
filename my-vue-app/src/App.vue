<script>
// This starter template is using Vue 3 <script setup> SFCs
// Check out https://vuejs.org/api/sfc-script-setup.html#script-setup

import AppHeader from "./components/AppHeader.vue";
import AppMain from "./components/AppMain.vue";
import AppNavBottom from "./components/AppNavBottom.vue";
import AppFooterTop from "./components/AppFooterTop.vue";
import AppFooterBottom from "./components/AppFooterBottom.vue";

export default {
  components: {

    AppHeader,
    AppMain,
    AppNavBottom,
    AppFooterTop,
    AppFooterBottom

  }
}
</script>

<template>
  <AppHeader />
  <AppMain />
  <AppNavBottom />
  <AppFooterTop />
  <AppFooterBottom />
</template>

<style scoped>
.logo {
  height: 6em;
  padding: 1.5em;
  will-change: filter;
}

.logo:hover {
  filter: drop-shadow(0 0 2em #646cffaa);
}

.logo.vue:hover {
  filter: drop-shadow(0 0 2em #42b883aa);
}
</style>
