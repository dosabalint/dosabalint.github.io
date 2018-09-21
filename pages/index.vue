<template>
<div v-html="content"></div>
</template>

<script>
  import content from "~/md/index.md";

  export default {
    computed: {
      content(){
        return content;
      }
    }
  }
</script>

<style>
  h1, h2, h3 {
    border-bottom: 1px solid gray;
  }
</style>
