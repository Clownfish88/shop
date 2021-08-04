<template>
  <div>
    <mt-swipe :auto="4000" class="swipe-banner">
      <mt-swipe-item><img src="@/assets/baner/ban1.jpg"/></mt-swipe-item>
      <mt-swipe-item><img src="@/assets/baner/ban2.jpg"/></mt-swipe-item>
      <mt-swipe-item><img src="@/assets/baner/ban3.jpg"/></mt-swipe-item>
    </mt-swipe>
  </div>
</template>
<script>
export default {
  name: 'banner',
  data(){
    return{

    }
  }
}
</script>
<style scoped>
.swipe-banner{
  height: 150px;
}
.swipe-banner img{
  width: 100%;
  height: auto;
}
</style>