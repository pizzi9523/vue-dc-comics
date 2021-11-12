<template>
  <div class="card col-2">
    <img :src="image" alt="" />
    <p>{{ titolo }}</p>
  </div>
</template>

<script>
export default {
  props: {
    image: String,
    titolo: String,
  },
};
</script>

<style lang="scss">
.card {
  img {
    height: 160px;
    width: 160px;
    object-fit: cover;
    object-position: top;
  }
  p {
    padding: 1rem 1rem 3rem 0;
    color: white;
  }
}
</style>