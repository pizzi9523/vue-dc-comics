<template>
  <main class="container-fluid">
    <div class="container">
      <div class="content">Content Goes here</div>
    </div>
    <MainFooter />
  </main>
</template>

<script>
import MainFooter from "./MainFooter.vue";

export default {
  components: {
    MainFooter,
  },
};
</script>

<style lang="scss">
@import "../assets/scss/variables.scss";

.container-fluid {
  background-color: $dark-content-color;
}
.content {
  color: white;
  padding: 100px 0;
  font-size: 20px;
}
</style>