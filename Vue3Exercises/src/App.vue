<script>
import User from './components/Employee.vue'
export default {
  data() {
    return {
      Users: [
        {
          id: 1,
          name: 'Ali',
          surn: 'Dzelyalov'
        },
        {
          id: 2,
          name: 'Ali',
          surn: 'Dzelyalov'
        },
        {
          id: 3,
          name: 'Ali',
          surn: 'Dzelyalov'
        },
      ],
    }
  },
  components: {
    User
  },
  methods: {
    add(name, surn){
      let id = this.Users.length + 1;
      this.Users.push({
        id, name, surn
      });
    }
  }
}
</script>

<template>
<User @add="add"/>
</template>


<style scoped>
</style>