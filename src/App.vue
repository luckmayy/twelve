<template>
  <div id="app">
    <!-- <el-container>
      <el-aside>
        <Menu></Menu>
      </el-aside>
      <el-main>
        <router-view/>
      </el-main>
    </el-container> -->
    <Menu></Menu>
      <!-- <img src="./assets/img/图片1.png"> -->
  </div>
</template>


<script>
// import HelloWorld from './components/HelloWorld.vue'
import Menu from './views/Menu.vue'


export default {
  name: 'App',
  components: {Menu}
}
</script>

<style>
 #app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
 
} 
</style>
