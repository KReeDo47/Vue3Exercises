<script>
export default{
data(){
  return{
    New: '',
    anythings: ['1', '2', '3', '4'],
  }
},
<script>
export default{
data(){
return{
    ballon: '',
    Ballon: ['Green', 'Wood', 'Grey'],
}
},
methods: {
removeBallon: function (index) {
    this.Ballon.splice(index, 1);
}
}
}
</script>

<template>
<ul>
<li v-for="(item, index) in 
			Ballon" :key="index">
    {{ item }}
    <br>
    <button @click="removeBallon(index)">remove</button>
</li>
</ul>
</template>

<style>
  
</style>