<template>
  <div id="app">
    <login></login>
  </div>
</template>

<script>
import Login from './views/Login.vue'
export default {
  name: 'app',
  components: {
    Login
  }
}
</script>

<style>
html{
  height: 100%;
}
body{
  height: 100%;
  margin: 0px;
}
#app{
  height: 100%;
  width: 100%;
}
</style>
