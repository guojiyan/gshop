<template>
  <div id="app">
    <router-view></router-view>
    <FootGuide v-show="$route.meta.showFooter"/>
  </div>
</template>

<script>
  import FootGuide from './components/FooterGuide/FooterGuide.vue'
export default{
  components: {
    FootGuide
  }
}
</script>

<style lang="stylus" rel="stylesheet/stylus">

</style>
