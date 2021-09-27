<script setup lang="ts">
// This starter template is using Vue 3 <script setup> SFCs
// Check out https://v3.vuejs.org/api/sfc-script-setup.html#sfc-script-setup
import HelloWorld from './components/HelloWorld.vue';
</script>

<template>
  <div class="container">
    <div class="left">left</div>
    <div class="right">right</div>
  </div>
</template>

<style>
* {
  padding: 0;
  margin: 0;
}
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
}
.container {
  display: flex;
  justify-content: space-between;
}
.left {
  background: purple;
  width: 20%;
  height: 100vh;
}
.right {
  flex: 1;
  background: orange;
  font-size: 18px; /*1.125*/
}
</style>
