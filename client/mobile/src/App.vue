<template>
  <div id="app">
    <van-tabbar route>
  <van-tabbar-item replace to="/" icon="home-o">首页</van-tabbar-item>
  <van-tabbar-item replace to="/search" icon="search">筛选</van-tabbar-item>
  <van-tabbar-item replace to="/about" icon="like-o">关于我</van-tabbar-item>
</van-tabbar>
    <router-view />
  </div>
</template>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
}

</style>
