<template>
  <div id="app">
    <img alt="freeCodeCamp Vienna logo" src="./assets/logo.png" class="logo-image">
    <StreamInfo />
  </div>
</template>

<script>
import StreamInfo from './components/StreamInfo'

export default {
  name: 'App',
  components: {
    StreamInfo
  }
}
</script>

<style>
body {
  background: #1b1b32;
}

#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #fff;
  margin-top: 60px;
}

.logo-image {
  height: 150px;
}
</style>
