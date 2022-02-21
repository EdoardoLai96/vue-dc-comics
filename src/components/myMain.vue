<template>
<main>
  <div class="container">

    <h1>--> Content goes here </h1>
  </div>
</main>
</template>

<script>
export default {
  name: 'myMain',
}
</script>

<style scoped lang="scss">
@import "../assets/style/variables.scss";

main{
  background-color: $secondaryColor;
  .container{
    padding: 60px 0;
    width: 70%;
    margin: auto;
      h1{
        color: white;
      }
  }
}

</style>
