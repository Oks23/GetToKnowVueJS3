<template>
<h1>Conditional Rendering Component</h1>
<h4 v-if="show">If Condition</h4>
<h4 v-else>Else Condition</h4>
<button v-on:click="show=!show">Click to change condition</button>
</template>

<script>
export default {
    name: 'ConditionalRenderingComponent',
    data() {
        return {
            show: true
        }
    }
}
</script>

<style scoped>
h1 {
    color: brown;
}
</style>
