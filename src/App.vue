<template>
  <div class="App">
    <HelloWorld></HelloWorld>
  </div>
</template>

<script>
import HelloWorld from './components/HelloWorld.vue'
export default {
  components: {
    HelloWorld
  }
}
</script>

<style>
.App{
  display: flex;
  height: 100vh;
  background-color: pink;
}
</style>