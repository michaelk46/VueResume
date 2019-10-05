<template>
    <div id="app" class="row">
        <div class="col-2"></div>
        <div id="mainColumn" class="col-6 red">
        <img alt="Vue logo" src="./assets/logo.png">
        <MainPanel/>
        </div>
        <div id="sideColumn" class="col-2 green">         
        <SidePanel msg="This is the Side Panel"/>
        </div>
        <div class="col-2"></div>
    </div>
</template>

<script>
  import MainPanel from './components/MainPanel.vue'
  import SidePanel from './components/SidePanel.vue'
  export default {
    name: 'Body',
    components: {
      MainPanel,
      SidePanel
    },    
  }
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
</style>