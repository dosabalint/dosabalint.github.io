<template>
  <div class="container">
    <Navigation/>
    <nuxt/>
  </div>
</template>

<script>
  import Navigation from "../components/Navigation";

  export default {
    components: {Navigation}
  }
</script>

<style lang="scss">
  @import '~bootstrap/scss/bootstrap';

  h1, h2, h3{
    margin-bottom: 1rem;
  }
</style>

