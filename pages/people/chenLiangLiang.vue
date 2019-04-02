<template>
  <section class="container">
    <div class="wraper">
      <h3 class="title">
        亮亮
      </h3>
      <div class="wrapper2">
        <div class="radius">
            <div class="radius1">
                <div class="radius2">
                 </div>
            </div>
        </div>
      </div>
      <ul class="information">
          <li class="informationli">
              <div class="height">172</div>
              <div class="heightext">身高</div>
         </li>
          <li class="informationli">
              <div class="height">1273</div>
              <div class="heightext">代谢</div>
          </li>
          <li class="informationli">
              <div class="height">55</div>
              <div class="heightext">体重</div>
          </li>
      </ul>
      <ul class="information1">
          <li class="information2">
              <div class="informationli2">三餐时间</div>
              <div class="informationli3">不确定</div>
          </li>
          <li class="information2">
              <div class="informationli2">睡眠时长</div>
              <div class="informationli3">8小时/天</div>
          </li>
          <li class="information2">
              <div class="informationli2">入睡时间</div>
              <div class="informationli3">凌晨1点</div>
          </li>
          <li class="information2">
              <div class="informationli2">起床时间</div>
              <div class="informationli3">9点</div>
          </li>
          <li class="information2">
              <div class="informationli2">运动基础</div>
              <div class="informationli3">无</div>
          </li>
          <li class="information2">
              <div class="informationli2">抽烟酗酒史</div>
              <div class="informationli3">抽烟初二开始</div>
          </li>
          <li class="information2">
              <div class="informationli2">家族遗传</div>
              <div class="informationli3">无</div>
          </li>
          <li class="information2">
              <div class="informationli2">身体状况</div>
              <div class="informationli3">死宅 中等偏下</div>
          </li>
          <li class="information2">
              <div class="informationli2">目标</div>
              <div class="informationli3">减脂 增肌 屁股</div>
          </li>
          <div class="null"></div>
      </ul>
    </div>
  </section>
</template>

<script>
import Logo from '~/components/Logo.vue'

export default {
  data() {
    return {
      todos: [
        { name: 123 },
        { name: '陈冠旭' }
      ]
    }
  },
  components: {
    Logo
  }
}
</script>

<style>
* {
  padding: 0;
  font-family: 'Avenir', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
}
.container {
  margin: 0 auto;
  min-height: 100vh;
  display: flex;
  justify-content: center;
  width: 100%;
}

.title {
  font-family: 'Avenir', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  display: block;
  font-weight: 600;
  font-size: 24px;
  color: #35495e;
  letter-spacing: 1px;
  margin-top: 20px;
}

.subtitle {
  font-weight: 300;
  font-size: 42px;
  color: #526488;
  word-spacing: 5px;
  padding-bottom: 15px;
}

.links {
  padding-top: 15px;
}

.nuxt-link-active{
  text-decoration: none;
}
.wrapper2 {
    display: flex;
    width: 100%;
    justify-content: center;
}
.radius {
  margin-top: 20px;
  width: 240px;
  height: 240px;
  border-radius: 50%;
  border: 1px solid;
  display: flex;
  justify-content: center;
  align-items: center;
  border: #DDE3FF 4px dashed;
}
.radius1 {
  width: 180px;
  height: 180px;
  border-radius: 50%;
  border: 1px solid;
  display: flex;
  justify-content: center;
  align-items: center;
  border: #E8E8E8 4px dashed;
}
.radius2 {
  animation:radiusanmation 5s;
  border-radius: 50%;
  background: #7990EF;
  box-shadow: #7990EF 1px 2px 10px;
  width: 110px;
  height: 110px;
  border-radius: 50%;
}
@keyframes radiusanimation
{
from {box-shadow: #7990EF 0px 0px 0px;}
to {box-shadow: #7990EF 1px 2px 30px;}
}
.wraper {
  justify-content: center;
  text-align: center;
  flex-direction: column;
  width: 80%;

}
.information {
    display: flex;
    list-style-type:none;
    justify-content: space-around;
    margin-top: 30px;
}

.height {
    font-size: 24px;
    font-weight: 600;
}
.heightext {
    font-size: 16px;
    color: #A4ADBF
}
.information1 {
    padding: 0;
    display: flex;
    list-style-type:none;
    flex-direction: column;
    align-items: flex-start;
    margin-top: 30px;
    
}
.information2 {

    width: 100%;
    display: flex;
    margin-top: 20px;
    padding-bottom: 20px;
    border-bottom: #EFEFEF 1px solid;
    justify-content: space-between;
}
.informationli2 {
    color: #707070;
}
.null {
    margin-top: 60px;
}
</style>
