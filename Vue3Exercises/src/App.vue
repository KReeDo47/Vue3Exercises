<script>
  export default{
    data(){
      return{
        age: 25,
      }
    }
  }
</script>
<template>
  <p v-if="age < 18">подросток</p> 
  <p v-else-if="19 < age && age < 25">молодой человек</p> 
  <p v-else="age > 26">мужчина</p> 
</template>


<style>
</style>