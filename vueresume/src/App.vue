<template>
  <div>
    <Header />    
    <Body />
  </div>
</template>

<script>
  import Header from './components/Header.vue'
  import Body from './components/Body.vue'
  export default {
    name: 'app',
    components: {
      Body,
      Header,
    },       
  }
</script>

<style>
  @import "./assets/css/application.css";
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
