<template>
  <div>
    <nuxt />
    <div class="navposition">
      <div class="nav">
        <nuxt-link to="/" class="button--blu">home</nuxt-link>
        <nuxt-link to="/info" class="button--blu">about</nuxt-link>
      </div>  
    </div>
  </div>
</template>
<script>
export default {
  transition: 'test'
}
</script>

<style>
html {
  font-family: 'Avenir', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  font-size: 16px;
  word-spacing: 1px;
  -ms-text-size-adjust: 100%;
  -webkit-text-size-adjust: 100%;
  -moz-osx-font-smoothing: grayscale;
  -webkit-font-smoothing: antialiased;
  box-sizing: border-box;
}

*,
*:before,
*:after {
  box-sizing: border-box;
  margin: 0;
}

.button--green {
  display: inline-block;
  border-radius: 4px;
  border: 1px solid #3b8070;
  color: #3b8070;
  text-decoration: none;
  padding: 10px 30px;
}
.button--blu {
  display: inline-block;
  color: #BFCCFF;
  text-decoration: none;
  padding: 10px 30px;
}
.button--blu:visited{
 text-decoration: none;
}
.button--blu:hover {
  color: #586BBA;
}

.button--green:hover {
  color: #fff;
  background-color: #3b8070;
}

.button--grey {
  display: inline-block;
  border-radius: 4px;
  border: 1px solid #35495e;
  color: #35495e;
  text-decoration: none;
  padding: 10px 30px;
  margin-left: 15px;
}

.button--grey:hover {
  color: #fff;
  background-color: #35495e;
}

.nuxt-link-active{
  text-decoration: none;
}
.navposition {
  position: fixed;
  bottom: 0;
  width: 100%;
  height: 50px;
  display: flex;
  justify-content: center;
  align-items: center;
  box-shadow: #E3E3E3 1px 2px 10px;
  text-decoration: none;
  
}
.nav {
  display: flex;
  justify-content: space-around;
  width: 100%;
}
</style>
