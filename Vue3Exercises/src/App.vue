<script>
export default{
data(){
return{
    products: [
			{
				id: 1,
				name: 'product1',
			},
			{
				id: 2,
				name: 'product2',
			},
			{
				id: 3,
				name: 'product3',
			},
		]
    }
}
}
</script>

<template>
  <p v-for="product in products" :key="product.id">
    {{ product.name }}
  </p>  
</template>
<style>
</style>