<template>
  <div class="header">
    <div class="header-left">
      <div class="iconfont icon-arrow-lift"></div>
    </div>
    <div class="header-input">
      <span class="iconfont icon-search"></span>
      請輸入城市名稱
      </div>
    <div class="header-right">
      城市
      <span class="iconfont icon-arrow-down"></span>
    </div>
  </div>
</template>

<script>
export default {
  name: 'HomeHeader'
}
</script>

<style lang="stylus" scoped>
  @import '../assets/styles/varibles.styl'
  .header
    display flex
    line-height .86rem
    font-size .32rem
    background-color #00BCD4
    color #fff
    .header-left
      width .64rem
      .icon-arrow-lift
        text-align center
        font-size .4rem
    .header-input
      flex 1
      height: .64rem
      line-height .64rem
      margin-top .12rem
      margin-left .2rem
      margin-right .2rem
      background-color #fff
      border-radius .1rem
      .icon-search
        padding-left .2rem
      color #ccc
    .header-right
      width 1.24rem
      text-align center
</style>
