<template>
  <div id="app">
    <m-header></m-header>
    <tab></tab>
  </div>
</template>

<script>
import MHeader from 'components/m-header/m-header.vue'
import Tab from 'components/tab/tab'
export default {
  data(){
      return {

      }
  },
  components:{
      MHeader,
      Tab
  }
}
</script>

<style lang="stylus" rel="stylesheet/stylus">
 // @import "common/stylus/index"

</style>
