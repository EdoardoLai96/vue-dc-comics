<template>
<section>
  <header>
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
  </header>
  <main>
  <div class="main">
    <div class="list_container_sx">
      <div class="list_container">
        <div class="upper_list">

      <h3 class="list_title">
        DC COMICS
      </h3>
      <ul class="list_body upper_list">
        <li>
          <a href="">Characters</a>
        </li>
        <li>
          <a href="">Comics</a>
        </li>
        <li>
          <a href="">Movies</a>
        </li>
        <li>
          <a href="">TV</a>
        </li>
        <li>
          <a href="">Games</a>
        </li>
        <li>
          <a href="">Videos</a>
        </li>
        <li>
          <a href="">News</a>
        </li>
      </ul>
      </div>
      <div class="lower_list"> 
        <h3>
          SHOP
        </h3>
      <ul class="list_body lower_list">
        <li>
          <a href="">Shop DC</a>
        </li>
        <li>
          <a href="">Shop Collectibles</a>
        </li>
      </ul>
      </div>

      </div>
      <div class="list_container">
      <h3 class="list_title">
        DC 
      </h3>
      <ul class="list_body">
        <li>
          <a href="">Terms Of Use</a>
        </li>
        <li>
          <a href="">Privacy policy (New)</a>
        </li>
        <li>
          <a href="">Ad Choices</a>
        </li>
        <li>
          <a href="">Advertising</a>
        </li>
        <li>
          <a href="">Jobs</a>
        </li>
        <li>
          <a href="">Subscriptions</a>
        </li>
        <li>
          <a href="">Talent Workshops</a>
        </li>
        <li>
          <a href="">CPSC Certificates</a>
        </li>
        <li>
          <a href="">Ratings</a>
        </li>
        <li>
          <a href="">Shop Help</a>
        </li>
      </ul>
      </div>
      <div class="list_container">
      <h3 class="list_title">
        DC 
      </h3>
      <ul class="list_body">
        <li>
          <a href="">DC</a>
        </li>
        <li>
          <a href="">MAD Magazine</a>
        </li>
        <li>
          <a href="">DC Kids</a>
        </li>
        <li>
          <a href="">DC Universe</a>
        </li>
        <li>
          <a href="">DC Power Visa</a>
        </li>
      </ul>
      </div>
    </div>
      <div class="list_container_dx">
        <img src="../assets/img/dc-logo-bg.png" alt="">
      </div>
  </div>

  </main>
  <footer>
    <div class="footer_sx">
      <div class="cta">SIGN-UP NOW</div>
    </div>
    <div class="footer_dx">
      <h3>FOLLOW US</h3>
      <div class="icon_box">
        <img src="../assets/img/footer-facebook.png">
      </div>
      <div class="icon_box">
        <img src="../assets/img/footer-twitter.png">

      </div>
      <div class="icon_box">
        <img src="../assets/img/footer-youtube.png">

      </div>
      <div class="icon_box">
        <img src="../assets/img/footer-pinterest.png">

      </div>
      <div class="icon_box">
        <img src="../assets/img/footer-periscope.png">

      </div>

    </div>
  </footer>
</section>
</template>

<script>

export default {
  name: 'mioFooter',
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

  header{
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
    main{
      background-image:url('../assets/img/footer-bg.jpg');
        a{
            color: #767F85;
        }
      .main{
        margin: auto;
        padding: 50px 15%;
        display: flex;
        position: relative;
        overflow: hidden;
        .list_container_sx{
          width: 50%;
          display: flex;
          overflow: hidden;
          h3{
            color: white;
            margin-bottom: 10px;
           margin-right: 20px;
          }
          .list_container{
           margin-right: 20px;
           li{
             margin-bottom: 10px;
           }
          }
        }
        .list_container_dx{
          img{
            position: absolute;
            top: -100px;
            right: 100px;
          }
        }
        }
    }
    footer{
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
}
</style>
