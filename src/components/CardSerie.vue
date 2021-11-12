<template>
  <div class="col-2">
    <div class="card">
      <img :src="image" alt="" />
      <p>{{ titolo }}</p>
    </div>
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
  margin: 1rem;
  img {
    height: 160px;
    width: 100%;
    object-fit: cover;
    object-position: top;
  }
  p {
    font-size: 13 px;
    padding: 1rem 0;
    color: white;
  }
}
</style>