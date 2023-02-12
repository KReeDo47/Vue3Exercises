<script>
  export default {
    data() {
      return {
        shekel: true,
      }
    },
    methods: {
      Shekel: function() {
        this.shekel = false;
      }
    }
  }
</script>

<template>
  <button @click="Shekel">Shekel</button>
  <div v-if="shekel">
  <p>Greg</p>
  <p>Ron</p>
  <p>Kai</p>
  </div>
</template>

<style>
</style>