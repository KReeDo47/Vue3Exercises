<script>
  export default {
    data() {
      return {
       arr1: ["x", "y", "z"],
       arr2: [1, 2, 3],
      }
    }
  }
</script>

<template>
  <div class="body">
    <div class="main"> 
      <p>{{ arr1[0] }}</p>
      <p>{{ arr1[1] }}</p>
      <p>{{ arr1[2] }}</p>
    </div>
    <div class="main">
      <p>{{ arr2[0] + arr2[1] + arr2[2] }}</p> 
    </div> 
  </div>     
</template>

