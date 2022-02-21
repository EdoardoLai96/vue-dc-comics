<template>
<header>
  <div class="container">

  <div class="logo_box">
    <img src="../assets/img/dc-logo.png" >
  </div>

    <ul class="nav">
      <li> 
        <a href="">CHARACTERS</a> 
      </li>

      <li> 
        <a href="">COMICS</a> 
      </li>

      <li> 
        <a href="">MOVIES</a> 
      </li>

      <li> 
        <a href="">TV</a> 
      </li>

      <li> 
        <a href="">GAMES</a> 
      </li>

      <li> 
        <a href="">COLLECTIBLES</a> 
      </li>

      <li> 
        <a href="">VIDEOS</a> 
      </li>

      <li> 
        <a href="">FANS</a> 
      </li>

      <li> 
        <a href="">NEWS</a> 
      </li>

      <li> 
        <a href="">SHOP</a> 
      </li>

    </ul>
  </div>

</header>  

</template>

<script>


export default {
  name: 'myHeader',
}
</script>

<style scoped lang="scss">
  @import "../assets/style/variables.scss";

  a{
    text-decoration: none;
  }
  .container{
    display: flex;
    height: 120px;
    justify-content: space-between;
    width: 70%;
    margin: auto;
    .logo_box{
      
      padding: 20px 0;
      img{
        height: 100%;
      }
    }
    ul{
      display: flex;
      align-items: center;

      li{
        list-style: none;
        height: 100%;
        margin: 0 15px;
        display: flex;
        align-items: center;
          border-bottom: 10px solid transparent;
          border-top: 10px solid transparent;
        &:hover{
          border-bottom: 10px solid $primaryColor;
          color: $primaryColor;
          transition: 0.3s;
          cursor: pointer;
        }
        &:hover a{
          color: $primaryColor;
          transition: 0.3s;
        }
        a{
          color: $secondaryColor;
          font-weight: bold;
        }
      }
    }
  }
</style>
