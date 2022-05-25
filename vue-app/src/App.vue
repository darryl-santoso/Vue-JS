<template>
  <div id="app">
    <CostDetail></CostDetail>
    <b-button variant="danger">Button</b-button>
  </div>
</template>

<script>
import CostDetail from './components/CostDetail.vue'
export default {
  name: 'App',
  components: {
    CostDetail
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
  border: solid;
}
</style>
