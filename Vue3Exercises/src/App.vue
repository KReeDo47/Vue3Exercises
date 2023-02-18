<script>
export default{
data(){
  return{
    order: '',
    visible: false,
    visible1: false,
    visible2: false,
  }
},
methods: {
one(){
      this.visible = true;
},
  two() {
    this.visible1 = true;
  },
  three() {
    this.visible2 = true;
  }
}
}
</script>

<template>
<div class="one">
<p>На чём вы играете?</p>
<input name="radio" type="radio" v-model="instrument" value="Гитара" @click="one">
<label for="">?</label>
<br>
<input name="radio" type="radio" v-model="instrument" value="Пиано" @click="two">
<label for="">?</label>
<br>
<input name="radio" type="radio" v-model="instrument" value="Скрипка" @click="three">
<label for="">?</label>
</div>

<p> Ваш выбор: {{ instrument }}</p>
<br>
</template>

<style scoped>
</style>
