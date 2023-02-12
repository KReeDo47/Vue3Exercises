<script>
  export default{
    data(){
      return{
        visible: true,
        visible2: true,
        visible3: true,
      }
    },
    methods: {
      Greg: function() {
        this.visible = !this.visible;
      },
      Son: function () {
        this.visible2 = !this.visible2;
      },
      Kai: function () {
        this.visible3 = !this.visible3;
      }
    }
  }
</script>

<template>
  <button @click="Greg">Greg</button>
  <p v-if="visible">Greg</p>
  <button @click="Son">Son</button>
  <p v-if="visible2">Son</p>
  <button @click="Kai">Kai</button>
  <p v-if="visible3">Kai</p>
  </template>

<style>
</style>