<script>
export default{
data(){
  return{
    obj: {Greg:'100$', Ron:'200$', Kai:'300$'},
  }
},
methods: {
}
}
</script>

<template>
  <ul class="styled">
    <li v-for="elem in obj">{{ elem }}</li>
  </ul>
  <br>
  <br>
  <ul class="styled">
    <li v-for="(key, elem) in obj"> {{ elem }} - {{ key }}</li>
  </ul>
  <br>
  <br>
  <ul class="styled">
    <li v-for="(key, elem, index) in obj"> {{ elem }} - {{ key }} - {{ index }}</li>
  </ul>
  <br>
  <br>
  <ul class="styled">
    <li v-for="(key, elem, index) in obj"> {{ elem }} - {{ key }} - {{ index+1 }}</li>
  </ul>
</template>

<style scoped>
</style>