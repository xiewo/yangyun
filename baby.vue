<template>
    <div class='nav'>
        <h2>我们都是木头人</h2>
  
       <ul  class='nav-item'>
          <li class='item-li'>
              <a href="javascript:;"><img src="./img/photo.png" alt=""></a>
               <p>照片图片</p>  
          </li>
          <li  class='item-li'>
              <a href="javascript:;"><img src="./img/record.png" alt=""></a>
               <p>记录</p>  
          </li>
          <li  class='item-li'>
              <a href="javascript:;"><img src="./img/weight.png" alt=""></a>
               <p>体重</p>  
          </li>
          <li  class='item-li'>
              <a href="javascript:;"><img src="./img/height.png" alt=""></a>
               <p>身高</p>  
          </li>
          <li  class='item-li'>
              <a href="javascript:;"><img src="./img/first.png" alt=""></a>
               <p>第一次</p>  
          </li>
          <li  class='item-li'>
              <a href="javascript:;"><img src="./img/sick.png" alt=""></a>
               <p>生病</p>  
          </li>
          <li  class='item-li'>
              <a href="javascript:;"><img src="./img/wounded.png" alt=""></a>
               <p>受伤</p>  
          </li>
          <li  class='item-li'>
              <a href="javascript:;"><img src="./img/sleep.png" alt=""></a>
               <p>宝宝语录</p>  
          </li>
          <li  class='item-li'>
              <a href="javascript:;"><img src="./img/breast.png" alt=""></a>
               <p>亲喂</p>  
          </li>
          <li  class='item-li'>
              <a href="javascript:;"><img src="./img/feed.png" alt=""></a>
               <p>瓶喂</p>  
          </li>
          <li  class='item-li'>
              <a href="javascript:;"><img src="./img/formula.png" alt=""></a>
               <p>配方奶</p>  
          </li>
           <li  class='item-li'>
              <a href="javascript:;"><img src="./img/rice.png" alt=""></a>
               <p>辅食</p>  
          </li>
           <li  class='item-li'>
              <a href="javascript:;"><img src="./img/nappy.png" alt=""></a>
               <p>尿布</p>  
          </li>
          <li  class='item-li'>
              <a href="javascript:;"><img src="./img/sleep.png" alt=""></a>
               <p>睡觉</p>  
          </li>
        </ul> 
    </div>
</template>



<script>
export default {
    data(){
        return{
        
        }
    },
    methods:{

    },
    match:{

    },
}
</script>



<style>
*{
    margin:0;padding:0;
}
.nav{
    width:375px; 
    height:100%;
    margin:0 auto;
}

ul.nav-item{
     width:375px; 
    margin:0 auto;
}

ul.nav-item  .item-li{
    float:left;
    list-style:none;
    width:125px;
    height:120px;
    text-align:center;
    border-bottom:1px solid #ddd;
    border-right:1px solid #ddd;
    box-sizing:border-box;
    padding:8px;
} 
li.item-li img{
    width: 60px;
    height:60px; 
    padding:5px;
}
li.item-li p{
    margin-top:5px;
}
 
</style>