<template>
    <div>
        <mt-tabbar v-model="selected" fixed>
      <mt-tab-item id="tab1">
        <img slot="icon" src="@/assets/index.png"> 首页
      </mt-tab-item>
      <mt-tab-item id="tab2">
        <img slot="icon" src="@/assets/03.png"> 会员
      </mt-tab-item>
      <mt-tab-item id="tab3">
        <img slot="icon" src="@/assets/04.png"> 购物车
      </mt-tab-item>
      <mt-tab-item id="tab4">
        <img slot="icon" src="@/assets/me.png"> 我的
      </mt-tab-item>
    </mt-tabbar>
    </div>
</template>
<script>
export default {
    name: 'tabbar',
    data(){
        return{
            selected: ''
        }
    }   
}
</script>