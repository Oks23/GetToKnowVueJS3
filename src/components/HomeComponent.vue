<template>
<h1>Home Component {{ email }}</h1>
<h4> passing param from main App.vue: {{ msgTest }}</h4>
</template>

<script>
export default {
    name: 'HomeComponent',
    props: {
        msgTest: String
    }
}
</script>

<style scoped>
h1 {
    color: blue;
}
</style>
