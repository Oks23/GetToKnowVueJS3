<template>
<h1>Parent Component</h1>
<ChildComponent name="test_name" :data="user" :getData="getData"/>
</template>

<script>
import ChildComponent from './ChildComponent.vue';
export default {
    name: "ParentComponent",
    components: { ChildComponent },
    data() {
        return {
            name: 'lorem',
            user: {
                name: 'test_name',
                email: 'test_email'
            }
        }
    },
    methods: {
                getData() {
                    console.log('function called')
                }
            }
}
</script>

<style scoped>
h1 {
    color: orangered;
}
</style>
