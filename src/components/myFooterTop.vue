<template>
    <section>
    <ul class="nav">
      <li> 
        <div class="img_box">
        <img src="../assets/img/buy-comics-digital-comics.png">
        </div>
        <a href="">DIGITAL COMISCS</a> 
      </li>

      <li> 
        <div class="img_box">
        <img src="../assets/img/buy-comics-merchandise.png">
        </div>
        <a href="">DC MERCHANDISE</a> 
      </li>

      <li> 
        <div class="img_box">
        <img src="../assets/img/buy-comics-subscriptions.png">
        </div>
        <a href="">SUBSCRIPTION</a> 
      </li>

      <li> 
        <div class="img_box">
        <img src="../assets/img/buy-comics-shop-locator.png">
        </div>
        <a href="">COMIC SHOP LOCATOR</a> 
      </li>

      <li> 
        <div class="img_box">
        <img src="../assets/img/buy-dc-power-visa.svg">
        </div>
        <a href="">DC POWER VISA</a> 
      </li>
    </ul>
  </section>

</template>

<script>
export default {
    name: 'myFooterTop',

}
</script>

<style scoped lang="scss">
@import "../assets/style/variables.scss";

  section{
   background-color: $primaryColor;
   padding: 50px 0;
   z-index: 9999;
   ul{
     width: 70%;
     margin: auto;
   display: flex;
   list-style: none;
     li{
      align-items: center;
      border-bottom: 10px solid transparent;
      border-top: 10px solid transparent;
      display: flex;
      justify-content: center;
      width: calc(100% / 5);
      margin-right: 5px;
      .img_box{
      display: inline-block;
      object-fit: contain;
      width: 50px;
      height: 50px;
        img{
        height: 100%;
        width: 100%;
        object-fit: contain;
        }
        }
        a{
          color: white;
          display: inline-block;
          margin-left: 10px;
          font-size: 0.8rem;
          white-space: nowrap;
          &:hover{
            text-decoration: underline;
          }
        }
        }
      }
    }

</style>