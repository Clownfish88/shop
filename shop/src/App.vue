<template>
  <div id="app">
    <!-- 标题栏 -->
    <mt-header title="标题过长会隐藏后面的内容啊哈哈哈哈">
      <router-link to="/" slot="left">
        <mt-button icon="back">返回</mt-button>
      </router-link>
      <mt-button icon="more" slot="right"></mt-button>
    </mt-header>
    <!-- banner -->
    <div>
      <Banner/>
    </div>
    <!-- 九宫格 -->
    <Grids/>
    <!-- 底部栏 -->
    <Tabbar/>
    <router-view/>
  </div>
</template>

<script>
import Banner from "./home/banner.vue"
import Grids from './home/grids.vue'
import Tabbar from './home/tabbar.vue'

export default {
  name: 'App',
  components:{
    Banner,
    Tabbar,
    Grids
    
  }
}
</script>

<style>

</style>
