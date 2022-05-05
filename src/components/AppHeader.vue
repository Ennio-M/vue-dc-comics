<template>
  <header>
    <div class="container">
      <nav>
        <div class="logo">
          <img src="../assets/imgs/dc-logo.png" alt="DC Logo">
        </div>
        <div class="navbar">
          <ul>
          <li>Characters</li>
          <li class="active">Comics</li>
          <li>Movies</li>
          <li>Tv</li>
          <li>Games</li>
          <li>Collectibles</li>
          <li>Videos</li>
          <li>Fans</li>
          <li>News</li>
          <li>Shop</li>
        </ul>
        </div>
      </nav>
    </div>
  </header>
</template>

<script>
export default {
  name: 'AppHeader'
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped lang="scss">
  @import '../style/variables.scss';
  @import '../style/general.scss';
  header{
   height: 120px;
   img{
     height: 100%;
   }
  }
  nav{
    height: 100%;
    display: flex;
    justify-content: space-between;
    align-items: center;
  }
  .logo{
    height: 100%;
    padding: 20px 0;
  }
  .navbar li{
    display: inline-block;
    padding: 14px;
    text-transform: uppercase;
    font-size: .9em;
    font-weight: 500;
  }
</style>
