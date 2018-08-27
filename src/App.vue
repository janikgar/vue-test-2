<template>
  <div id="app">
    <HeadLine />
    <PainTable />
  </div>
</template>

<script>
import PainTable from './components/PainTable'
import HeadLine from './components/HeadLine'
// import PainTable from './components/PainTable'

export default {
  name: 'App',
  components: {
    HeadLine,
    PainTable
  }
}
</script>

<style>
@import 'bootstrap/dist/css/bootstrap.css';
@import 'bootstrap-vue/dist/bootstrap-vue.css';
#app {
  font-family: 'Avenir', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
