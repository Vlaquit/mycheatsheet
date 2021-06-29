<template>
  <div id="app">
    <CommandBlock command-line="git init [project name]" description="Create a new local repository. If [project name] is provided, Git will create a new directory name [project name] and will initialize a repository inside it. If [project name] is not provided, then a new repository is initialized in the current directory"/>
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
  margin-top: 30px;
}
</style>
