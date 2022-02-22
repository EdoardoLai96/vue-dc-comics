<template>

<header>
  <div class="logo_box">
    <img src="../assets/img/dc-logo.png" >
  </div>
    <ul class="nav">
      <li v-for = "(nav_item, index) in nav_items" :key="index">
        <a href="">{{nav_item}}</a>
      </li>
    </ul>
</header>  

</template>

<script>
export default {
  name: 'myHeader',
  data (){
    return{
      nav_items: [
        "CHARACTERS",
        "COMICS",
        "MOVIES",
        "TV",
        "GAMES",
        "COLLECTIBLES",
        "VIDEOS",
        "FANS",
        "NEWS",
        "SHOP",
      ]
    }
  }
}
</script>

<style scoped lang="scss">
  @import "../assets/style/variables.scss";

  a{
    text-decoration: none;
  }
  header{
    display: flex;
    justify-content: space-between;
    padding: 0 15%;
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
