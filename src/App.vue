<template>
  <div id="app">
  <router-link to="/">Home</router-link>|
  <router-link to="/contact">Contact</router-link>|
  <router-link to="/project">Project</router-link>
  
    <router-view />
  </div>
</template>

<script>
export default {
   name: 'App',

   data: () => ({
      //
   })
}
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: palevioletred;
  margin-top: 60px;
  
}
.router-link-exact-active {
  color: purple;
}

</style>