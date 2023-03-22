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
<br /> <br />
<BindingGetInputValueComponent />
<br /> <br />
<GetValueFromCheckboxRadiobtnComponent />
<br /> <br />
<ConditionalRenderingComponent />
<br /> <br />
<ForLoopAndListComponent />
</template>

<script>
import HelloWorld from './components/HelloWorld.vue'
import HomeComponent from './components/HomeComponent.vue'
import InterpolationAndDataComponent from './components/InterpolationAndData.vue'
import MethodsWithParamComponent from './components/MethodsWithParamComponent.vue'
import EventsExamplesComponent from './components/EventsExamplesComponent.vue'
import BindingGetInputValueComponent from './components/BindingGetInputValueComponent.vue'
import GetValueFromCheckboxRadiobtnComponent from './components/GetValueFromCheckboxRadiobtnComponent.vue'
import ConditionalRenderingComponent from './components/ConditionalRenderingComponent.vue'
import ForLoopAndListComponent from './components/ForLoopAndListComponent.vue'

export default {
    name: 'App',
    components: {
        HelloWorld,
        HomeComponent,
        InterpolationAndDataComponent,
        MethodsWithParamComponent,
        EventsExamplesComponent,
        BindingGetInputValueComponent,
        GetValueFromCheckboxRadiobtnComponent,
        ConditionalRenderingComponent,
        ForLoopAndListComponent
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
