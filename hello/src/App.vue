<template>
  <div id="app">
      <Title/>
      <Baner/>
  </div>
</template>

<script>
import Title from './components/Title.vue'
import Baner from './components/Baner.vue'
export default {
  name: 'App',
  components: {
    Title,
    Baner
  }
}
</script>

<style lang="scss">
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
