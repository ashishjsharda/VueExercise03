<template>
  <div>
    <h1>Exercise 1-03</h1>
    <p>Click the button to change the text.</p>
    <button @click="changeText">Change Text</button>
    <p>{{ text }}</p>
  </div>
</template>

<script>
export default {
  name: "Exercise1-03"
}
</script>

<style lang="scss" scoped>
@import '../styles/typography.css';
h1{
  font-size: 50px;
  color: blue;

}
</style>