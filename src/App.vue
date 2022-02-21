<template>
  <div id="app">
    <myHeader/>
    <myMain/>
    <mioFooter/>
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
  font-family: sans-serif;
}
</style>
