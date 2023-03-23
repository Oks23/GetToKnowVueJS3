<template>
<h2>Child Component</h2>
<p>{{ name }}</p>
<p>{{ data.email }}</p>
<button v-on:click="getData()">Click here</button>
</template>

<script>
export default {
    name: 'ChildComponent',
    props: {
        name: String,
        data: Object,
        getData: Function,
    }
}
</script>

<style scoped>
h2 {
    color: green;
}
</style>
