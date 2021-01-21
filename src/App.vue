<template>
  <div id="app">
    <img alt="Vue logo" src="./assets/logo.png">
    <MyElement msg="Use ElementUI"/>
    <My msg="Liu Hongtian" />
    <HelloWorld msg="Welcome to Your Vue.js App"/>
    <MyNavi />
    <el-calendar />
    <MyTable />
  </div>
</template>

<script>
import HelloWorld from './components/HelloWorld.vue'
import My from './components/My.vue'
import MyElement from './components/MyElement.vue'
import MyNavi from './components/MyNavi.vue'
import MyTable from './components/MyTable.vue'

export default {
  name: 'App',
  components: {
    HelloWorld,
    My,
    MyElement,
    MyNavi,
    MyTable
  }
}
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
