<template>
  <img alt="Vue logo" src="./assets/logo.png">
  <HelloWorld msg="Welcome to Your Vue.js App"/>
  <MiComponente></MiComponente>
  <ComponentOne></ComponentOne>
  <ComponentTwo></ComponentTwo>
  <ComponentThree></ComponentThree>
</template>

<script>
import HelloWorld from './components/HelloWorld.vue'
import MiComponente from './components/MiComponente.vue'
import ComponentOne from './components/ComponentOne.vue'
import ComponentTwo from './components/ComponentTwo.vue'
import ComponentThree from './components/ComponentThree.vue'


export default {
  name: 'App',
  components: {
    HelloWorld,
    MiComponente,
    ComponentOne,
    ComponentTwo,
    ComponentThree

}
}
</script>

<style>
/*
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
*/
/* Carga de estilo de styles.css*/
@import './assets/css/styles.css';
</style>
