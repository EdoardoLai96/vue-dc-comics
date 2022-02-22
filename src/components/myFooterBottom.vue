<template>


  <section>
    <div class="footer_sx">
      <div class="cta">SIGN-UP NOW</div>
    </div>
    <div class="footer_dx">
      <h3>FOLLOW US</h3>
      <div class="icon_box" v-for = "(icon, index) in icons" :key="index">
        <img :src= icon>
      </div>
    </div>
  </section>
</template>

<script>

export default {
  name: 'mioFooter',
  data(){
    return{
      icons: [
        "../assets/img/footer-facebook.png",
        "../assets/img/footer-twitter.png",
        "../assets/img/footer-youtube.png",
        "../assets/img/footer-pinterest.png",
        "../assets/img/footer-periscope.png",
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
li{
  list-style: none;
}
    section{
      background-color: $secondaryColor;
      padding: 20px 15%;
      display: flex;
      justify-content: space-between;
      color: white;
      .footer_sx{
        display: flex;
        align-items: center;
        padding: 10px;
        border: 2px solid $primaryColor;
        &:hover{
          border-color: white;
          transition: 0.4s;
          cursor: pointer;
        .cta{
          transition: 0.4s;
          color: $primaryColor;
        }
        }
        .cta{
          height: min-content;
        }

      }
      .footer_dx{
        display: flex;
      h3{
        margin-right: 15px;
        color: $primaryColor;
        height: min-content;
      }
        align-items: center;
      .icon_box{
        margin-right: 15px;
      }
      }
    }
</style>
