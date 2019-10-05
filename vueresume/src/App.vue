<template>
  <Body />
</template>

<script>
  import Body from './components/Body.vue'
  export default {
    name: 'app',
    components: {
      Body,
    },       
  }
</script>

<style>
  @import "./assets/css/application.scss";
  .yellow {
    background-color: yellow;
  }
  .blue {
    background-color: blue;
  }
  .red {
    background-color: red;
  }
  .green {
    background-color: green;
  }
</style>
