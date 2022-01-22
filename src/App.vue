<template>
  <div id="app">
    <!-- <PagePc/> -->
    <PageMobile/>
  </div>
</template>

<script>
import PagePc from "./components/PagePc.vue"
import PageMobile from "./components/PageMobile.vue"
export default {
  name: "app",
  components:{
    PagePc,
    PageMobile
  }
}
</script>

<style lang="less">
#app {
  // * {
  //   margin: 0;
  //   padding: 0;
  // }
}
</style>
