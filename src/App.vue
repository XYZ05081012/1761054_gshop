<template>
  <div id="app">
    <router-view/>
    <FooterGuide v-if="$route.path==='/msite' || $route.path==='/order' || $route.path==='/search' || $route.path==='/profile' "/>
  </div>
</template>

<script>

  import FooterGuide from './components/FooterGuide/FooterGuide.vue'

  export default {

    components: {
      FooterGuide
    }
  }
</script>
<style lang="stylus" rel="stylesheet/stylus">

</style>
