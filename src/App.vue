<template>
  <div id="app">
    <div id="nav">
      <div class="left">
        <router-link tag="button" to="/">Home</router-link>
      </div>
      <div class="right">
        <router-link tag="button" :to="{name:'signup'}">Sign Up</router-link>
        <router-link tag="button" :to="{name:'signin'}">Sign In</router-link>
      </div>
    </div>
    <router-view />
  </div>
</template>

<style lang="scss">
* {
  box-sizing: border-box;
}
body {
  padding: 0;
  margin: 0;
  width: 100%;
  height: 100%;
  position: fixed;
}
#app {
  font-family: "Avenir", Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
}
#nav {
  position: fixed;
  width: 100%;
  margin: 0;
  -webkit-box-shadow: 0px 0px 10px 0px rgba(0, 0, 0, 0.75);
  -moz-box-shadow: 0px 0px 10px 0px rgba(0, 0, 0, 0.75);
  box-shadow: 0px 0px 10px 0px rgba(0, 0, 0, 0.75);
  a {
    font-weight: bold;
    color: #2c3e50;
    &.router-link-exact-active {
      color: #42b983;
    }
  }
  div {
    display: inline;
  }
  button {
    border-radius: 20px;
    padding: 10px;
    margin: 5px;
  }
  .left {
    float: left;
  }
  .right {
    float: right;
  }
}
input,
.input {
  border-radius: 20px;
  padding: 10px;
  margin: 10px;
}
.view {
  position: absolute;
  width: 100%;
  height: calc(100% - 50px);
  top: 50px;
  padding: 10px;
}
</style>
