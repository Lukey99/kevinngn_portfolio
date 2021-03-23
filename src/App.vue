<template>
  <div id="app">
    <Main/>
  </div>
</template>

<script>
import Main from "./components/main/main"

export default {
  name: 'App',
  components: {
    Main
  }
}
</script>

<style>
body{
  overflow: hidden;
}

.router-view{
  position: absolute;
  overflow-x: hidden;
  overflow-y: auto;
  left: 200px;
  top: 0;
  height: 100%;
  width: 1720px;
}
</style>
