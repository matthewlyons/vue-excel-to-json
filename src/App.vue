<template>
  <div id="app">
    <img alt="Vue logo" src="./assets/logo.png" />
    <Header />
    <DropZone />
  </div>
</template>

<script>
import Header from './components/Header.vue';
import DropZone from './components/DropZone.vue';
export default {
  name: 'App',
  components: {
    Header,
    DropZone
  }
};
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
