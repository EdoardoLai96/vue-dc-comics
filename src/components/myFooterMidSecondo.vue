<template>
<section>
    <div class="list_container_sx">
      <ul v-for = "(list, index) in lists" :key="index">
        <h3>{{list.title}}</h3>
        <li v-for = "(item, index) in list.items" :key="index">
          <a href="">{{item}}</a>
        </li>
      </ul>
    </div>

      <div class="list_container_dx">
        <img src="../assets/img/dc-logo-bg.png" alt="">
      </div>
</section>

</template>

<script>
export default {
name: "myFooterMid",
    data (){
    return{
      lists : [
        {
        title : "DC COMICS",
        items : [
            "Characters",
            "Comics",
            "Movies",
            "TV",
            "Games",
            "Videos",
            "News",
                ]
        },
        {
        title : "SHOP",
        items : [
            "Shop DC",
            "Shop DC Collectibles",
                ]
        },
        {
        title : "DC",
        items : [
            "Terms of Use",
            "Privacy policy (New)",
            "Ad Choices",
            "Advertising",
            "Jobs",
            "Subscriptions",
            "Talent Workshops",
            "CPSC Certificates",
            "Ratings",
            "Shop Help",
            "Contact Us",
                ]
        },
        {
        title : "SITES",
        items : [
            "DC",
            "MAD Magazine",
            "DC Kids",
            "DC Universe",
            "DC Power Visa",
                ]
        },

      ]
    }
  }

}
</script>

<style scoped lang="scss">
    section{
      background-image:url('../assets/img/footer-bg.jpg');
        a{
            color: #767F85;
            &:hover{
              text-decoration: underline;
            }
        }
        margin: auto;
        padding: 50px 15%;
        display: flex;
        position: relative;
        overflow: hidden;
        .list_container_sx{
          width: 50%;
          display: flex;
          overflow: hidden;
          ul{
            margin: 0 10px;
          h3{
            color: white;
            margin-bottom: 10px;
           margin-right: 20px;
          }
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

</style>>
