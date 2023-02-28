<template>
  <div>
    <img alt="Vue logo" src="./assets/logo.png">
      <div id="hlava"></div>
      <div id="torso"></div>
      <div id="bottom"></div> 

  </div>
</template>

<script>

import Hlava from './components/Hlava.vue';
import Chest from './components/Chest.vue';
import Bottom from './components/Bottom.vue';

export default{
   name: 'App',
   components: {
    Hlava,
    Chest,
    Bottom
  }
}
</script>

<style>
#head{
  width: 100px;
}
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
