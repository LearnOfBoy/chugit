<template>
<div class="Header">
  <div class="Header-left">
<div class="iconfont back-icon">&#xe624;</div>
  </div>
  <div class="Header-body">
<span class="iconfont">&#xe632;</span>
输入城市/景点/游玩主题
  </div>
  <div class="Header-right">城市
<span class="iconfont arrow-icon">&#xe638;</span>
  </div>
</div>
</template>

<script>
export default{
  name: 'HomeHeader'
}
</script>

<style lang="stylus" scoped>
@import '~style/varibles.styl'
.Header
  display: flex
  line-height: .86rem
  background: $bgColor
  color: #fff
.Header-left
  width: .64rem
  float: left
.Header-right
  width: 1.24rem
  float: right
  text-align:center
.arrow-icon
  font-size:.24rem
.back-icon
  text-align:center
  font-size: .4rem
.Header-body
  margin-left: .12rem
  padding-left: .2rem
  heigh: .64rem
  line-height: .64rem
  margin-top: .12rem
  margin-bottom: .12rem
  flex: 1
  background: #fff
  border-radius: .1rem
  color: #ccc
</style>
