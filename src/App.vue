<template>
  <div id="app">
    <SiteHeader />
    <!-- <img alt="Vue logo" src="./assets/logo.png">
    <HelloWorld msg="Welcome to Your Vue.js App"/> -->
  </div>
</template>

<script>
import SiteHeader from "./components/SiteHeader.vue";

export default {
  name: "App",
  components: {
    SiteHeader,
  },
};
</script>

<style lang="scss">
#app {
  font-family: "Greta Sans Condensed Bold", "Greta Sans Bold", Arial, sans-serif;
}
</style>
