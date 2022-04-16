<template>
  <div id="app">
    <UserHome/>
  </div>
</template>

<script>
import UserHome from './components/UserHome.vue'


export default {
  name: 'App',
  components: {
    UserHome
    
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
  background-color: rgb(0,0,0);
  height: 97.5vh;
  width: 99vw;
}
</style>
