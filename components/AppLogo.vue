<template>
  <div class="VueToNuxtLogo">
     <div class="log">知乎</div>
     <div class="login"><nuxt-link to="/login">注册或登录</nuxt-link></div>
  </div>
</template>

<style >
.VueToNuxtLogo{
  width: 100%;
  height: 50px;
  line-height: 50px;
  display: flex;
  justify-content: space-between;
  
}
.log{
  color: aqua;
  font-size: 34px;
}
.login a{
  color: blue;
  text-decoration: none;
}
.VueToNuxtLogo div{
    padding: 0 10px;
  }
</style>

