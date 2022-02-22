<template>
  <div id="app">
    <myHeader/>
    <myMain/>
    <myFooterTop/>
    <myFooterMidSecondo/>
    <myFooterBottom/>
  </div>
</template>

<script>
import myHeader from './components/myHeader.vue'
import myMain from './components/myMain.vue'
import myFooterTop from './components/myFooterTop.vue'
import myFooterMidSecondo from './components/myFooterMidSecondo.vue'
import myFooterBottom from './components/myFooterBottom.vue'

export default {
  name: 'App',
  components: {
    myHeader,
    myMain,
    myFooterBottom,
    myFooterTop,
    myFooterMidSecondo,
  }
}
</script>

<style lang="scss">

@import "./assets/style/general.scss";
#app {
  font-family: sans-serif;
}
</style>
