<script>
export default{
data(){
return{
    days: [],
}
}
}
</script>

<template>
<div>
<input type="checkbox" v-model="days" value="Monday">
<label>Monday</label>
<br>
<input type="checkbox" v-model="days" value="Thursday">
<label>Thursday</label>
<br>
<input type="checkbox" v-model="days" value="Wednesday">
<label>Wednesday</label>
<ol>
<li v-for="elem in days">{{ elem }}</li>
</ol>
</div>
<br>
</template>

<style>
  
</style>
