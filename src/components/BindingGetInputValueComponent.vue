<template>
<h1>Binding Get Input Value Component </h1>
<input type="text" v-model="data" />
<h4>Data ftom input: {{ data }}</h4>
<hr />
<br /> <br />
<input type="email" placeholder="enter email" v-model="email" />
<br /> <br />
<input type="password" placeholder="enter password" v-model="password" />
<br /> <br />
<button type="button" v-on:click="getData()">Get Data:</button>
</template>

<script>
export default {
    name: 'BindingGetInputValueComponent',
    data() {
        return {
            data: 121,
            email: null,
            password: null
        }
    },
    methods: {
        getData() {
            console.log("button clicked, values - ", this.email, this.password)
        }
    }
}
</script>

<style scoped>
h1 {
    color: darkgrey;
}
</style>
