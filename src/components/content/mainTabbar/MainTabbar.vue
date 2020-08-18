<template>
  <div id="app">
    <tab-bar>
      <tab-bar-item path="/home">
        <img slot="item-icon" src="~assets/img/tabbar/index.svg" alt="">
        <img slot="item-icon-active" src="~assets/img/tabbar/index1.svg" alt="">
        <div slot="item-text">首页</div>
      </tab-bar-item>

      <tab-bar-item path="/category">
        <img slot="item-icon" src="~assets/img/tabbar/category.svg" alt="">
        <img slot="item-icon-active" src="~assets/img/tabbar/category1.svg" alt="">
        <div slot="item-text">分类</div>
      </tab-bar-item>

      <tab-bar-item path="/cart">
        <img slot="item-icon" src="~assets/img/tabbar/gouwuche.svg" alt="">
        <img slot="item-icon-active" src="~assets/img/tabbar/gouwuche1.svg" alt="">
        <div slot="item-text">购物车</div>
      </tab-bar-item>

      <tab-bar-item path="/profile">
        <img slot="item-icon" src="~assets/img/tabbar/my.svg" alt="">
        <img slot="item-icon-active" src="~assets/img/tabbar/my1.svg" alt="">
        <div slot="item-text">我的</div>
      </tab-bar-item>

    </tab-bar>
  </div>
</template>

<script>
  import TabBar from 'components/common/tabbar/TabBar'
  import TabBarItem from 'components/common/tabbar/TabBarItem'
  export default {
    name: 'App',
    components:{
      TabBar,
      TabBarItem
    }
  }
</script>

<style>
  @import "../../../assets/css/base.css";
</style>
