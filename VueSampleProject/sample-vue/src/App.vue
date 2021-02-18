<template>
<div>
  <img id = "calculator-image" alt="Calculator logo" src="./assets/calculator.png"><br>
  Hira 
  <rootComponentVue />
</div>
</template>

<script>
import rootComponentVue from './components/root-component.vue';

export default {
  name: 'App',
  components:{
    rootComponentVue
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
#calculator-image
{
  width: 100px;
  height: 100px;
}
</style>
