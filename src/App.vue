<template>
  <div id="app">
    <mioFooter/>
    <myHeader/>
    <myMain/>
  </div>
</template>

<script>
import myHeader from './components/myHeader.vue'
import myMain from './components/myMain.vue'
import mioFooter from './components/mioFooter.vue'




export default {
  name: 'App',
  components: {
    myHeader,
    myMain,
    mioFooter,
  }
}
</script>

<style lang="scss">

@import "./assets/style/general.scss";
#app {
  width: 70%;
  margin: auto;
  font-family: sans-serif;
}
</style>
