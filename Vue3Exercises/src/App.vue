<script>
export default{
data(){
  return{
    items: [1, 2, 3],
  }
},
methods: {
}
}
</script>

<template>
  <div v-for="elem in items">
  <p class="hunter">{{ elem }}</p>
  <p class="divider"> </p>
  </div>
  <br>
  <ul class="styled" v-for="elem in items">
    <li>{{ elem }}</li>
    <li class="divider"> </li>
  </ul>
</template>

<style scoped>
</style>