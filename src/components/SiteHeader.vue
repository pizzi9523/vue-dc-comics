<template>
  <header id="site_header">
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
  </header>
  <!-- /#site_header -->
</template>
    
<script>
export default {};
</script>

<style lang="scss">
@import "../assets/scss/variables.scss";

#site_header {
  display: flex;
  padding: 40px;
  justify-content: space-around;

  .navbar {
    display: flex;
    align-items: center;

    ul {
      display: flex;
      list-style: none;
      li {
        margin: 0 1rem;
        padding: 1rem 0;
        font-size: 20px;

        &.active {
          border-bottom: 8px solid $primary-color;
        }
      }
    }
  }
}
</style>