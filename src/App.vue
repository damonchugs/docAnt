<template>
  <div id="app">
    <img alt="Vue logo" src="./assets/logo.png">
    <a-button type="primary">Hello world!</a-button>
  </div>
</template>

<script>
import HelloWorld from './components/HelloWorld.vue'
import { Button } from 'ant-design-vue';
export default {
  name: 'app',
  components: {
    HelloWorld,
    'a-button': Button
  }
}
</script>

<style lang="less" scoped>
  #app {
    font-family: 'Avenir', Helvetica, Arial, sans-serif;
    -webkit-font-smoothing: antialiased;
    -moz-osx-font-smoothing: grayscale;
    text-align: center;
    color: #2c3e50;
    margin-top: 60px;
  }
</style>
