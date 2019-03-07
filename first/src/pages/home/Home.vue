<template>
<div>
<home-header></home-header>
<home-swipwe></home-swipwe>
<home-icons></home-icons>
</div>
</template>
<script>
import HomeHeader from './components/Header'
import HomeSwipwe from './components/Swipwe'
import HomeIcons from './components/Icons'
export default{
  name: 'Home',
  components: {
    HomeHeader,
    HomeSwipwe,
    HomeIcons
  }
}
</script>
<style>
</style>
