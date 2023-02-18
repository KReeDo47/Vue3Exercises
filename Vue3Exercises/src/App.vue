<script>
export default{
data(){
  return{
    checked: true, 
  }
},
methods: {
Klark: function () {
    this.checked = false;
    this.visible = !this.visible;
},
}
}
</script>

<template>
<input class="text-field__input" type="checkbox" v-model="checked"> 
<button @click="Klark">Klark</button>
<p v-if="visible">{{ checked ? 'Green' : 'Wood' }}</p>
</template>

<style>
</style>

