<template>
<h1 v-on:mousemove="getConsole()">Events Examples Component Component {{ email }}</h1>
<button v-on:click="getDataButton('btn 1 clicked')">Click here 1</button>
<button v-on:dblclick="getDataButton('btn 2 clicked')">Click here 2</button>
<h2>Count: {{ count }}</h2>
</template>

<script>
export default {
    name: 'EventsExamplesComponent',
    data() {
        return {
            count: 0
        }
    },
    methods: {
        getDataButton(data) {
            this.count = this.count + 1;
            console.log(data)
        },
        getConsole() {
            console.log("hover worked")
        }
    }
}
</script>

<style scoped>
h1 {
    color: orange;
}
</style>
