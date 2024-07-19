<template>
  <div class="box">
    <h1>App Root Component-peter</h1>
    <h1>Add a new title</h1>
  </div>
</template>
<script lang="ts" setup name="App">
  const str = 'I Love China'
  for (let i = 0; i < 10; i++) {
    console.log('hello vue')
  }
</script>
<style scoped>
  .box {
    width: 600px;
    height: 400px;
    background-color: black;
  }
  h1 {
    color: white;
  }
</style>
