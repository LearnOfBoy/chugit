<template>
<div class="warapper">
<swiper :options="swiperOption">
<swiper-slide v-for='item of swiperList' :key='item.id'>
    <img class="swiper-img" :src="item.imgUrl" />
</swiper-slide>
  <div class="swiper-pagination"  slot="pagination"></div>
  </swiper>
</div>
</template>
<script>
export default{
  name: 'HomeSwipwe',
  data () {
    return {
      swiperOption: {
        pagination: '.swiper-pagination',
        loop: true
      },
      swiperList: [{
        id: '0001',
        imgUrl: 'http://mp-piao-admincp.qunarzz.com/mp_piao_admin_mp_piao_admin/admin/20191/a211765c0bb579b18c6e7d6d75997a48.jpg_750x200_b6921fa6.jpg'
      }, {
        id: '0002',
        imgUrl: 'http://mp-piao-admincp.qunarzz.com/mp_piao_admin_mp_piao_admin/admin/20191/61e0c45bd6f46af63f03fc19af63fd57.jpg_750x200_21f214c6.jpg'
      }]
    }
  }
}
</script>
<style lang='stylus' scoped>
.warapper >>> .swiper-pagination-bullet-active
  background: #fff
.warapper
  overflow: hidden
  width: 100%
  height:0
  padding-bottom: 26.9%
  .swiper-img
    width: 100%
 </style>
