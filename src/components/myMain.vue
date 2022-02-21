<template>
<main>
    <h1>--> Content goes here </h1>

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
  padding: 60px 0;
  h1{
    color: white;
  }
}

</style>
