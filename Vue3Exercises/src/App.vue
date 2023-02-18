<script>
  export default{
    data(){
      return{
        isValid: true,
        isDisabled: true,
      }
    }
  }
</script>
<template>
  <p :class="{valid: isValid, disabled: isDisabled}">text</p>
</template>

<style>
  
</style>