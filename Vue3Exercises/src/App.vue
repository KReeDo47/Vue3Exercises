<script>
export default{
data(){
return{
    Names: ['Flex','Alex','Frank']
}
},
methods: {
add: function(){
this.Names.push('Liza');
},
del: function(){
this.Names.shift();
},
del1: function () {
this.Names.pop();
},
splice: function(){
this.Names.splice(2, 1);
},
sort: function(){
this.Names.sort();
},
reverse: function () {
    this.Names.reverse();
},
}
}
</script>

<template>
<ul>
<li v-for="elem in Names">{{ elem }}</li>
</ul>
<button @click="add">1</button>
<br>
<button @click="del">2</button>
<br>
<button @click="del1">3</button>
<br>
<button @click="splice">4</button>
<br>
<button @click="sort">5</button>
<br>
<button @click="reverse">6</button>
</template>

<style>
</style>