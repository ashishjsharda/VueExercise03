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

<style scoped>

</style>