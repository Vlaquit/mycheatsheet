<template>
  <div id="app">
    <CommandBlock msg="$ git init [project name]"/>
  </div>
</template>

<script>
import CommandBlock from "@/components/CommandBlock";
export default {
  name: 'App',
  components: {
    CommandBlock
  }
}
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: left;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
