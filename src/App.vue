<template>
  <div id="app">
    <img alt="Vue logo" src="./assets/logo.png">

    <button class="button is-primary">Hello</button>
  </div>
</template>

<script>
export default {
  name: 'App',
  components: {
//    HelloWorld
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

  button {
      font-size: 5em;
  }
}
</style>
