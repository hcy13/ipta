<template>
  <div id="app">
    <div id="nav">
      <router-link to="/">Home</router-link> |
      <router-link to="/about">學士班</router-link>|
      <router-link to="/stu">招生</router-link>|
      <router-link to="/news">最新消息</router-link>|
      <router-link to="/connect">聯絡我們</router-link>|
    </div>
    <router-view/>
  </div>
</template>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  font-size: 12px;
  background-color: black;
}

#nav {
  width:100vw;
  text-align:right;
  padding: 30px;
  padding-top: 70px;
  left:0px;
}

#nav a {
  font-weight: bold;
  color: #FFFFFF;
}

#nav a.router-link-exact-active {
  color:coral;
}
</style>
