<template>
<h1>Methods With Param Component {{ email }}</h1>
<h4>NameFunction: {{ getName("Test here") }}</h4>
<h4>getDataTestObject: {{ getData() }}</h4>
<h4>getDataTestName: {{ getData().name }}</h4>
<h4>getDataTestEmail: {{ getData().email }}</h4>
<h4>getDataTestEmailFromPreviousReturnFunc: {{ getData().emailFromPreviousReturnFunc }}</h4>
</template>

<script>
export default {
    name: 'MethodsWithParamComponent',
    props: {
        msgTest: String
    },
    data() {
        return {
            count: 0
        }
    },
    methods: {
        getName(x) {
            return x
        },
        getData() {
            return {
                name: "test",
                email: 'test1@gmail.com',
                emailFromPreviousReturnFunc: this.email
            }
        },
    }
}
</script>

<style scoped>
h1 {
    color: purple;
}
</style>
