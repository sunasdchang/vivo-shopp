<template>
<div class="main">
  <h2>爆款产品</h2>
  <div class="main_box">
    <ul>
      <img src="https://shopstatic.vivo.com.cn/vivoshop/commodity/20180405/20180405101609299910_original.jpg" width="100%">
    </ul>
  </div>
</div>
</template>

<script>
  import { mapState, mapMutations, mapGetters } from "vuex";
  export default {
        name: "HomeContainer"
    }
</script>

<style lang="stylus" scoped>
.main h2
  display block
  height 13rem
  line-height 1.3rem
  background white
  font-size 0.35rem
  padding-left 0.3rem
  .main_box
    height 339px
</style>
