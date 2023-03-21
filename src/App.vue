<template>
<img alt="Vue logo" src="./assets/logo.png">
<HelloWorld msg="passing params test with variable" />
<br /> <br />
<HomeComponent msgTest="3232323232" />
<br /> <br />
<InterpolationAndDataComponent />
<br /> <br />
<MethodsWithParamComponent />
<br /> <br />
<EventsExamplesComponent />
</template>

<script>
import HelloWorld from './components/HelloWorld.vue'
import HomeComponent from './components/HomeComponent.vue'
import InterpolationAndDataComponent from './components/InterpolationAndData.vue'
import MethodsWithParamComponent from './components/MethodsWithParamComponent.vue'
import EventsExamplesComponent from './components/EventsExamplesComponent.vue'

export default {
    name: 'App',
    components: {
        HelloWorld,
        HomeComponent,
        InterpolationAndDataComponent,
        MethodsWithParamComponent,
        EventsExamplesComponent
    }
}
</script>

<style>
#app {
    font-family: Avenir, Helvetica, Arial, sans-serif;
    -webkit-font-smoothing: antialiased;
    -moz-osx-font-smoothing: grayscale;
    text-align: center;
    color: #2c3e50;
    margin-top: 60px;
}
</style>
