<template>
  <div id="app">
    <router-view></router-view>
  </div>123
</template>

<script>
import HelloWorld from './components/HelloWorld.vue'
// qiqiqi
export default {
  name: 'App',
  components: {
    HelloWorld
  }
}
</script>

<style>
  * {
    --themeColor:#ea4245;
  }
</style>
