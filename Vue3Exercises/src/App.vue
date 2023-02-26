<script>
import Ali from './components/Employee.vue'
export default {
  data() {
    return {
      name: 'Ali',
      surn: 'Dzelyalov',
    }
  },
  components: { Ali }
}
</script>

<template>
<Ali :name="name" :surn="surn"/>
</template>

<style>
</style>
