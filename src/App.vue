<template>
  <div id="app">
    <img alt="Robots playing games" src="./assets/raider-robots.jpg">

    <h1 class="title">
        Hello Raiders!
    </h1>

    <p>
        The winds of change are blowing and we've decided it's time to rebrand our camp.<br>
        But we have a problem...
    </p>

    <p>
        Choice paralysis is a flaw of the human mind where people tasked with choosing between many possible options have trouble making any decision at all.
        So far we've already come up with a list of over 50 new names for our camp.
        With a camp of only about 25 people, a simple voting process would inevitably lead to many posisble names getting tied or having no votes at all.
    </p>

    <p>
        This tool was created to define an objective scoring system we can use to rank potential camp names and reduce the total number of options to choose from.
    </p>

    <p>
        If you are curious, lists of all suggested camp names and scoring criteria can be found below.
        Or click "Start Scoring" to jump right in and start ranking your favorite camp names!
    </p>

    <div class="buttons">
        <button class="button">Review All Camp Names</button>
        <button class="button">Review Scoring Criteria</button>
        <button class="button is-primary">Start Scoring</button>
    </div>
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
  text-align: left;
  color: #2c3e50;
  margin: 5em auto;
  max-width: 640px;

  p {
      margin-bottom: 1em;
  }
}
</style>
