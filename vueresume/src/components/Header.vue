<template>
    <div id="header" class="row">
        <div class="col-2"></div>
        <div id="fields" class="col-8">
            <div id="fullName" class="col-12"><!--<i class="fa fa-user-o" aria-hidden="true"></i>--> {{ fullName }} </div>             
            <div id="emailAddress" class="col-12"> {{ emailAddress }} <i class="fa fa-envelope-o" aria-hidden="true"></i></div> 
            <div id="location" class="col-12"> <!--<i class='fa fa-address-card-o'></i>--> {{ location }} </div> 
        </div>
        <div class="col-2"></div>
    </div>
</template>

<script>
  export default {
    name: 'Header',
    components: {
    }, 
    data() {
        return {
            fullName: 'Michael Kinder',
            emailAddress: 'michaelk46@gmail.com',
            location: 'Cincinnati, Ohio'
        }
    },
  }
</script>

<style scoped>
</style>