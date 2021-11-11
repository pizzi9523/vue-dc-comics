<template>
  <div class="container-fluid">
    <div class="container">
      <div class="content">Content Goes here</div>
    </div>
    <div class="main_footer">
      <div class="container">
        <div class="card">
          <div class="img_wrapper">
            <img src="../assets/img/buy-comics-digital-comics.png" alt="" />
          </div>
          <p class="card_text">DIGITAL COMICS</p>
        </div>
        <div class="card">
          <div class="img_wrapper">
            <img src="../assets/img/buy-comics-merchandise.png" alt="" />
          </div>
          <p class="card_text">DC MERCHANDISE</p>
        </div>
        <div class="card">
          <div class="img_wrapper">
            <img src="../assets/img/buy-comics-shop-locator.png" alt="" />
          </div>
          <p class="card_text">SUBSCRIPTION</p>
        </div>
        <div class="card">
          <div class="img_wrapper">
            <img src="../assets/img/buy-comics-subscriptions.png" alt="" />
          </div>
          <p class="card_text">COMIC SHOP LOCATOR</p>
        </div>
        <div class="card">
          <div class="img_wrapper">
            <img src="../assets/img/buy-dc-power-visa.svg" alt="" />
          </div>
          <p class="card_text">DC POWER VISA</p>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {};
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
.main_footer {
  background-color: $primary-color;
  .container {
    display: flex;
    justify-content: space-around;
    gap: 30px;
    padding: 60px 0;
    .card {
      display: flex;
      align-items: center;
      color: white;
      gap: 10px;
      img {
        width: 50px;
        height: 50px;
        object-fit: contain;
      }
    }
  }
}
</style>