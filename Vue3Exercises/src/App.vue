<script>
  export default {
    data() {},
    methods: {
      show: function (x) {
        alert(x ** 2);
      },
    },
  };  
</script>

<template>
  <div class="body">
    <div class="main">
      <button @click="show(2)">2</button>
    </div>
    <div class="main">
      <button @click="show(3)">3</button>
    </div>   
  </div>     
</template>

