<template>
  <div id="app">
    <h1>{{title}}</h1>
    <h2>{{subtitle}}</h2>
  </div>
</template>

<script>



export default {
  name: 'App',
  data() {
    return {
      title: 'Exercise 1-03',
      subtitle: 'Click the button to change the text.'
    }
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
