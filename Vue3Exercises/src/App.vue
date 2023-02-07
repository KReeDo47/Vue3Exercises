<script>
  export default {
    data() {
      return {
        cost: "85",
        amount: "15",
      };
    },
    methods: {
      change: function (i) {
        this.cost = this.cost + 1;
      },
    },
    computed: {
      price: function() {
        return this.cost * this.amount;
      }, 
    },
  };  
</script>

<template>
  <div class="body">
    <div class="main">
      <p>{{ cost }}</p>
      <p>{{ amount }}</p>
      <p>{{ price }}</p>
    </div>   
    <div class="main">
      <button @click="change(cost)">+</button>
    </div>  
  </div>     
</template>

