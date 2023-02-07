<script>
  export default {
    data() {
      return {
        visible: true,
      };
    },
}; 
</script>

<template>
  <div class="body">
    <div class="main">
      <p v-if="visible">Ali</p>
    </div>   
    <div class="main">
      <p v-if="!visible">Ali</p>
    </div>  
  </div>     
</template>


