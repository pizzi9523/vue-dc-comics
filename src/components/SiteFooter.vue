<template>
  <footer>
    <div class="top-footer container-fluid">
      <div class="container">
        <div class="row">
          <div class="links">
            <div class="col-3">
              <h2>DC COMICS</h2>
              <ul>
                <li><a href="">Lorem.</a></li>
                <li><a href="">Quae?</a></li>
                <li><a href="">Necessitatibus?</a></li>
                <li><a href="">Velit!</a></li>
                <li><a href="">Error.</a></li>
                <li><a href="">Autem.</a></li>
                <li><a href="">Quam.</a></li>
              </ul>

              <h2>SHOP</h2>
              <ul>
                <li><a href="">Lorem.</a></li>
                <li><a href="">Similique.</a></li>
              </ul>
            </div>
            <div class="col-3">
              <h2>DC</h2>
              <ul>
                <li><a href="">Lorem.</a></li>
                <li><a href="">Quae?</a></li>
                <li><a href="">Necessitatibus?</a></li>
                <li><a href="">Velit!</a></li>
                <li><a href="">Error.</a></li>
                <li><a href="">Autem.</a></li>
                <li><a href="">Quam.</a></li>
                <li><a href="">Lorem.</a></li>
                <li><a href="">Dignissimos?</a></li>
                <li><a href="">Vel!</a></li>
                <li><a href="">Ullam?</a></li>
              </ul>
            </div>
            <div class="col-3">
              <h2>SITES</h2>
              <ul>
                <li><a href="">Lorem.</a></li>
                <li><a href="">Quae?</a></li>
                <li><a href="">Necessitatibus?</a></li>
                <li><a href="">Velit!</a></li>
                <li><a href="">Error.</a></li>
              </ul>
            </div>
          </div>
        </div>
      </div>
    </div>
    <div class="bottom-footer container-fluid">
      <div class="container">
        <div class="row">
          <div class="sign-up">SIGN-UP NOW!</div>

          <div class="social">
            <p>FOLLOW US</p>

            <img src="../assets/img/footer-facebook.png" alt="" />
            <img src="../assets/img/footer-twitter.png" alt="" />
            <img src="../assets/img/footer-youtube.png" alt="" />
            <img src="../assets/img/footer-pinterest.png" alt="" />
            <img src="../assets/img/footer-periscope.png" alt="" />
          </div>
        </div>
      </div>
    </div>
  </footer>
</template>

<script>
export default {};
</script>

<style lang="scss">
@import "../assets/scss/variables.scss";

footer {
  .top-footer {
    //   height: 600px;
    background: url("../assets/img/dc-logo-bg.png") 90%,
      url("../assets/img/footer-bg.jpg");
    background-size: 730px, cover;
    background-repeat: no-repeat;
    .row {
      justify-content: space-between;

      .links {
        display: flex;
        gap: 50px;
        padding: 80px 0;
        width: calc(100% / 2);

        h2 {
          color: white;
          padding: 20px 0;
        }
        ul {
          list-style: none;
          li {
            padding: 5px 0;
            a {
              text-decoration: none;
              color: $link-color;
              font-size: 1rem;
            }
          }
        }
      }
    }
  }
  .bottom-footer {
    background-color: $dark-footer-bg;

    .row {
      justify-content: space-between;
      align-items: center;
      padding: 40px 0;
      .sign-up {
        color: white;
        padding: 10px;
        border: 1px solid $primary-color;
        font-weight: bold;
      }
      .social {
        display: flex;
        align-items: center;
        gap: 20px;
        p {
          color: $primary-color;
          font-weight: bold;
        }
      }
    }
  }
}
</style>