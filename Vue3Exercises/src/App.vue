<script>
  export default {
    data() {
      return {
        text: "Ali",
      };
    },
    methods: {
      change: function (i) {
        this.text = this.text + " " + "Ali";
      },
      achange: function (i) {
        this.text = "Ali";
      },
    },
  };  
</script>

<template>
  <div class="body">
    <div class="main">
      <p>{{ text }}</p>
    </div>
    <div class="main">  
      <button @click="change(text)">+</button>
    </div>
    <div class="main">
      <button @click="achange(text)">-</button>
    </div>   
  </div>     
</template>

