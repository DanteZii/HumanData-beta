
<template>
    <section class="container2">
        <h1 class="h1k">HumanData</h1>
        <div class="wrapper">
          <nuxt-link to='/people/chenguanxu' class="alink">
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

