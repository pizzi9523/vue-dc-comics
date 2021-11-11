<template>
  <header id="site_header">
    <div class="container">
      <div class="logo">
        <img src="../assets/img/dc-logo.png" alt="" />
      </div>

      <nav class="navbar">
        <ul>
          <li><a href=""></a>CHARACTERS</li>
          <li class="active"><a href=""></a>COMICS</li>
          <li><a href=""></a>MOVIES</li>
          <li><a href=""></a>TV</li>
          <li><a href=""></a>GAMES</li>
          <li><a href=""></a>COLLECTIBLES</li>
          <li><a href=""></a>VIDEOS</li>
          <li><a href=""></a>FANS</li>
          <li><a href=""></a>NEWS</li>
          <li><a href=""></a>SHOP</li>
        </ul>
      </nav>
    </div>
  </header>

  <!-- /#site_header -->
</template>
    
<script>
export default {};
</script>

<style lang="scss">
@import "../assets/scss/variables.scss";

#site_header {
  .container {
    display: flex;
    justify-content: space-between;
  }

  .logo {
    padding: 1rem 0;
  }

  .navbar {
    display: flex;
    align-items: center;

    ul {
      display: flex;
      list-style: none;
      height: 100%;

      li {
        margin: 0 1rem;
        font-size: 1rem;
        font-weight: bold;
        height: 100%;
        line-height: 140px;

        &.active {
          border-bottom: 4px solid $primary-color;
        }
      }
    }
  }
}
</style>