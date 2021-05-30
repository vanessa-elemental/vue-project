<template>
  <div id="app">
    <Home/>
  </div>
</template>

<script>
import Home from './components/Home.vue'

export default {
  name: 'App',
  components: {
    Home
  }
}
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  background: #E5E5E5;
  color: #2C98F0;
  text-align: center;
}

.text-muted {
  color: #6C757D;
}

input{
  padding: 9px 16px 7px !important;
  background: #FFFFFF;
  border: 1px solid #E9ECEF;
  border-radius: 1px;
}

button {
  background: #2C98F0 !important;
  box-shadow: 0px 1px 3px rgba(0, 0, 0, 0.05);
  border-radius: 4px;
}
</style>
