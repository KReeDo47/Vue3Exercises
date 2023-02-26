<script>
export default {
    emits: ['show', 'show1'],
    data() {
        return {
        }
    },
    methods: {
        handleName() {
            this.$emit('show', 'Ali',);
        },
        handleSalary(){
            this.$emit('show1', 'Dzelyalov', '20000');
        }
    }
}
</script>

<template>
<button class="button" @click="handleName">Ali</button>
<button class="button" @click="handleSalary">Dzelyalov</button>
</template>