
<template>
    <section class="container2">
        <h1 class="h1k">HumanData</h1>
        <div class="wrapper">
          <nuxt-link to='/personinfo' class="alink">
              <ul class="wriper">
                  <li class="image"></li>
                  <li class="name">陈冠旭</li>
              </ul>
          </nuxt-link>    
          <nuxt-link to='/people/chenhan' class="alink">
              <ul class="wriper">
                  <li class="image"></li>
                  <li class="name">陈晗</li>
              </ul>
          </nuxt-link>
          <nuxt-link to='/' class="alink">
              <ul class="wriper">
                  <li class="image"></li>
                  <li class="name">郭慧琳</li>
              </ul>
          </nuxt-link>
          <nuxt-link to='/' class="alink">
              <ul class="wriper">
                  <li class="image"></li>
                  <li class="name">蛇皮</li>
              </ul>
          </nuxt-link> 
          <nuxt-link to='/' class="alink">
              <ul class="wriper">
                  <li class="image"></li>
                  <li class="name">姜敬伟</li>
              </ul>
          </nuxt-link>
          <nuxt-link to='/' class="alink">
              <ul class="wriper">
                  <li class="image"></li>
                  <li class="name">王泽华</li>
              </ul>
          </nuxt-link>
          <nuxt-link to='/' class="alink">
              <ul class="wriper">
                  <li class="image"></li>
                  <li class="name">子慕</li>
              </ul>
          </nuxt-link>
          <nuxt-link to='/people/chenLiangLiang' class="alink">
              <ul class="wriper">
                  <li class="image"></li>
                  <li class="name">陈亮亮</li>
              </ul>
          </nuxt-link>
          <nuxt-link to='/' class="alink">
              <ul class="wriper">
                  <li class="image"></li>
                  <li class="name">小田</li>
              </ul>
          </nuxt-link>
        </div>
        <h1></h1>
        <h1></h1>
        <h1></h1>           
    </section>
</template>
<style>

* {
  margin: 0;
  text-align: center;
  color: #2c3e50;
  background-color: #fff;
}
h1 {
    margin-top: 20px;
}
.container2 {
  min-height: 20vh;
  display: flex;
  justify-content: center;
  text-align: center;
  flex-direction: column;
  

}
.wrapper {
  display: flex;
  flex-direction: column;
  width: 100%;
  justify-content: center;
}
.alink{
  text-decoration: none;
  display: flex;
  justify-content: center;
}
.wriper {
  margin-top: 6px;
  margin-bottom: 6px;
  width: 90%;
  height: 90px;
  background-color: #fff;
  border-radius: 8px;
  box-shadow: #e8e8e8 1px 2px 6px ;
  display: flex;
  align-items: center;
  list-style-type:none;
}
.image {
  width: 50px;
  height: 50px;
  border-radius: 50%;
  background: #7990EF;
  box-shadow: #7990EF 1px 2px 6px;
  margin-left: 10px;

}
.name {
  margin-left: 30px;

}
.h1k {
  margin-bottom: 10px;
}


</style>

<script>
export default {
  
  data() {
    return{
      todolist: [
        { name: '陈冠旭',},
        { name: '陈晗'},
        { name: '郭慧琳'},
        { name: '蛇皮'},
        { name: '王泽华'},
        { name: '子慕'},
        { name: '姜敬伟'},
        { name: '亮亮'},
        { name: '小田'},

      ]
    }
  }
}
</script>

