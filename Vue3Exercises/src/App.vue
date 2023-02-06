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
  {{ show() }}
  <div class="body">
    
    <div class="main"></div>
  </div>     
</template>

