<template>
  <div id="app">
    <h1>{{title}}</h1>
    <h2>{{subtitle}}</h2>
    <ul>
      <li> {{items[0]}}</li>
      <li> {{items[1]}}</li>
      <li> {{items[2]}}</li>

    </ul>
  </div>
</template>

<script>
export default {
  name: 'App',
  data() {
    return {
      title: 'Exercise 1-03',
      subtitle: 'Click the button to change the text.',
      items: ['Item 1', 'Item 2', 'Item 3']
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
