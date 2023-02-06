<script>
  export default {
    data() {
      return {
        str: "string",
      };
    },
    methods: {
      show: function () {
        var i = new Date();
        alert(this.cape(i.getDay()));
      },
      cape: function (num) {
        switch (num) {
          case 0:
          return "Monday";
        case 1:
          return "Tuesday";
        case 2:
          return "Wednesday";
        case 3:
          return "Thursday";
        case 4:
          return "Friday";
        case 5:
          return "Saturday";
        case 6:
          return "Sunday";
        default:
          return "Error";
        }
      },
    },
  };  
</script>

<template>
  <div class="body">
    <div class="main">
      <button @click="show()">This place</button>
    </div>
  </div>     

</template>

