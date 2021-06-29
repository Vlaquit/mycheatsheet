<template>
  <div>
    <p>{{ description }}</p>
    <code>
      {{ commandLine }}
    </code>
  </div>
</template>

<script>
export default {
  name: "CommandBlock",
  props: {
    commandLine: String,
    description: String
  }
}
</script>

<style scoped>
div {
  background-color: #fafafa;
  size: 200px;
  position: center;
  border-radius: 7px;
  padding: 10px;
}
code{
  background-color: #eee;
  border-radius: 7px;
  font-family: courier, monospace;
  padding: 10px;
}
</style>