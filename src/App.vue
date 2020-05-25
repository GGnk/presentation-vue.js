<template>
  <div id="app">
    <RevealComponent/>
  </div>
</template>

<script>
  import RevealComponent from './components/Reveal.vue'

  export default {
    name: 'App',
    components: {
      RevealComponent
    },
  }
</script>

<style>
  #app {
    font-family: 'Avenir', Helvetica, Arial, sans-serif;
    -webkit-font-smoothing: antialiased;
    -moz-osx-font-smoothing: grayscale;
    text-align: center;
    color: #2c3e50;
    /* margin-top: 60px; */
    height: 100vh;
  }
</style>
