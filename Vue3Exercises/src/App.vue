<script>
import Ali from './components/Employee.vue'
export default {
  data() {
    return {
      
    }
  },
  components: {
    Ali
  },
  methods: {
    Ali() {
      alert('1, 2, 3, 4');
    },
    Dzelyalov(){
      alert('1, 2, 3, 4')
    }
  }
}
</script>

<template>
<Ali @show="Ali" @show1="Dzelyalov" />
</template>


<style>
</style>