<template>
  <div id="app">
    <img src="./assets/logo.png">
    <component-a label="testing external component" />
  </div>
</template>

<script>
import ExternalComponents from 'vuejs-component-lib'

export default {
  name: 'app',
  components: {
    ComponentA: ExternalComponents.ComponentA
  }
}
</script>

<style>
#app {
  font-family: 'Avenir', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
