<template>
  <div id="app">
    <img alt="Vue logo" src="./assets/hack.png">
   <Formulario />
   <Menu />
  </div>
</template>

<script>
import Formulario from './components/Formulario.vue'
import Menu from './components/Menu.vue'
export default {
  

  name: 'App',
  components: {
   Formulario,
   Menu
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
