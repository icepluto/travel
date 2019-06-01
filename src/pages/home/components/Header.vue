<template>
<div class="header">
  <div class="header-left">返回</div>
  <div class="header-input"> 输入城市/游玩/主题</div>
  <div class="header-right">城市</div>
</div>
</template>

<script>
export default {
  name: 'HomeHeader'
}
</script>

<style lang="stylus" scoped>
  .header
    display flex
    line-height 2.86rem
    background-color #00bcd4
    color #ffffff
    .header-left
      width 2.64rem
      float left
    .header-input
      flex 1
      background #fff
      height 1.8rem
      line-height 1.8rem
      border-radius .5rem
      margin-top 0.5rem
      margin-left 0.5rem
      color #cccccc
    .header-right
      width 4.24rem
      float right
      text-align center

</style>
