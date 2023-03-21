<template>
<h1>Interpolation and Data Component {{ email }}</h1>
<h4>E-mail: {{ email }}</h4>
<h4>Mobile: {{ mobile }}</h4>
<h4>NameFunction: {{ getName("Test here") }}</h4>
</template>

<script>
export default {
    name: 'InterpolationAndDataComponent',
    props: {
        msgTest: String
    },
    data() {
        return {
            email: "test@gmail.com",
            mobile: 1010101001010,
            count: 0
        }
    },
    methods: {
        getName(x) {
            return x
        }
    }
}
</script>

<style scoped>
h1 {
    color: green;
}
</style>
