<template>
  <div id="app">
    <h2>{{message}}</h2>
  </div>
</template>

<script>

export default {
  name: 'App',
  data() {
    return{
      message: '我是APP组件'
    }
  },
  components: {
    
  }
}
</script>

<style>
@import "./assets/css/base.css";
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
