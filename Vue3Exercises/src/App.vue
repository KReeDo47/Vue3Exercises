<script>
  export default {
    data() {
      return {
       num: 5,
       num: 1,
       num: 2,
       num: 3,
      }
    }
  }
</script>

<template>
  <div class="body">
    <div class="main"> 
      <p>{{ num ** 2 }}</p>
    </div>
    <div class="main">
      <p>{{ num1 + num2 + num3 }}</p> 
    </div> 
  </div>     
</template>

