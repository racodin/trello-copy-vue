<template>
  <div id="app">
    <AppHeader/>
    <BoardContainer/>
  </div>
</template>

<script>
import AppHeader from "@/components/AppHeader"
import BoardContainer from "@/components/BoardContainer"
export default {
  name: 'app',
  components: {
    AppHeader,
    BoardContainer
  }
}
</script>

<style>
html {
  height: 100%;
  width: 100%;
}
body {
  height: 100%;
  width: 100%;
  margin: 0;
  padding: 0;
  background-color: #444;
}
#app {
  font-family: 'Avenir', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
}
</style>
