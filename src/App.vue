<template>
  <NavComponent/>
  <router-view/>
</template>

<script>

import NavComponent from "@/components/NavComponent";
export default {
  name: 'App',
  components: {
    NavComponent
  }
}
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
}
</style>
