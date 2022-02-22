<template>
  <div class="card_box">
      <img :src="img">
      <h4 class="card_title">{{serie}}</h4>
  </div>
</template>

<script>
export default {
name: "myCard",
props: {
    "img" : String,
    "serie": String
    }
}
</script>

<style scoped lang="scss">
    .card_box{
        width: 200px;
        height: 200px;
        margin-bottom: 100px;
        margin-left: 15px;
        margin-right: 15px;
        position: relative;
        
        .card_title{
            text-align: center;
            text-transform: uppercase;
            color: white;
            text-align: left;
        }
        img{
            width: 100%;
            height: 100%;
            object-fit: cover;
            object-position: top;
            margin-bottom: 20px;

        }
    }
</style>