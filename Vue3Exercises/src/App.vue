<script>
  export default{
    data(){
      return{
        isAuth: true,
      }
    },
    methods: {
      Shekel: function(){
        this.isAuth = false;
      }
    }
  }
</script>
<template>
  <button @click="Shekel">Shekel</button>
  <p v-show="isAuth">text</p>
</template>

<style>
</style>