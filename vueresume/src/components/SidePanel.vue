<template>
  <div class="side">
    <PanelInsert/>
  </div>
</template>

<script>
  import PanelInsert from './PanelInsert.vue'

  export default {
    name: 'SidePanel',
    components: {
      PanelInsert
    },
    props: {
      msg: String
    }
  }
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
</style>