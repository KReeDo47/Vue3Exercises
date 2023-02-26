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
    remove(id) {
      this.Users = this.Users.filter((User) => {
        return User.id !== id;
      })
    }
  }
}
</script>
<template>
<User v-for   ="User in Users"
		:id     ="User.id"
		:name   ="User.name"
		:surn   ="User.surn"
		@remove ="remove"
		:key    ="User.id"/>
</template>

<style scoped>
</style>