<template>
  <div id="app">
    <router-view></router-view>
    <MainTabBar/>
  </div>
</template>

<script>
import MainTabBar from './components/MainTabBat'
export default {
  name: 'app',
  components: {
    MainTabBar
  }
}
</script>

<style>
  @import "./assets/css/base.css";
  
 

</style>
