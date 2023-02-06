<script>
  export default {
    data() {},
    methods: {
      show: function () {
        var date = new Date();
        alert(date);
      }
    }
  }
</script>

<template>
  <div class="body">
    <div class="main">
      <button @click="show()">This place</button>
    </div>
    <div class="main">
      <button v-on:mousover="show()">Come here</button>
    </div>    
  </div>     
</template>

