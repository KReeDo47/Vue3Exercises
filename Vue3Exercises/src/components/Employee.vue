<script>
export default {
    props: ['name'],
    data() {
        return {
        }
    }
}
</script>

<template>
  <ul class="one">
    <li v-for="Ali in name">{{ Ali }}</li>
  </ul>
</template>