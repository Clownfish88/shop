<template>
    <div class="list">
        <ul>
            <li id="list-01">
                <a href=""><img src="@/assets/grids/01.png" alt=""></a>
                <span>新闻资讯</span>
            </li>
            <li id="list-02">
                <a href=""><img src="@/assets/grids/02.png" alt=""></a>
                <span>图文分享</span>
            </li>
            <li id="list-03">
                <a href=""><img src="@/assets/grids/03.png" alt=""></a>
                <span>商品展示</span>
            </li>
            <li id="list-04">
                <a href=""><img src="@/assets/grids/04.png" alt=""></a>
                <span>资讯</span>
            </li>
            <li id="list-05">
                <a href=""><img src="@/assets/grids/05.png" alt=""></a>
                <span>联系我们</span>
            </li>
        </ul>
        <div style="clear:both;"></div>
    </div>
</template>
<script>
export default {
    name: 'grids',
    data(){
        return{

        }
    }
}
</script>

<style scoped>
.list ul {
    width: 100%;
    padding: 0;
}
.list ul li{
    list-style: none;
    float: left;
    width: 29%;
    text-align: center;
    background-color:#ccc;
    border-radius: 10px;
    padding: 0 0 12px;
    margin:0 2% 10px;
}
.list ul li a{
    display: inline-block;
    padding: 8px 15px 0;
}
.list ul li a img{
    width: 100%;
    padding: 0;
}
.list ul li span{
    display: block;
    font-size: 14px;
    color: #fff;
    line-height: 14px;
}
#list-01{
    background-color: #36A1DB;
}
#list-02{
    background-color: #81B637;
}
#list-03{
    background-color: #E57E22;
}
#list-04{
    background-color: #7E54DC;
}
#list-05{
    background-color: #00B699;
}
</style>