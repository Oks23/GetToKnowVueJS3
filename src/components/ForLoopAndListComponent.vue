<template>
<h1>For Loop And List Component</h1>
<ul>
    <li v-for="item in array_1" :key="item">
        {{ item }}
    </li>
</ul>
<br /> <br />
<ul>
    <h4>Elements in the loop: </h4>
    <li v-for="item in array_2" :key="item.subitem_1">
        <p>item first subitem: {{ item.subitem_1 }}</p>
        <p>item second subitem: {{ item.subitem_1 }}</p>
        <p>item third subitem: {{ item.subitem_1 }}</p>
        <p>item fourth subitem: {{ item.subitem_1 }}</p>
        <br /><br />
    </li>
</ul>
</template>

<script>
export default {
    name: 'ForLoopAndListComponent',
    data() {
        return {
            array_1: [
                'option_1',
                'option_2',
                'option_3',
                'option_4',
                'option_5'
            ],
            array_2: [{
                    subitem_1: 'option__1',
                    subitem_2: 'option__2',
                    subitem_3: 'option__3',
                    subitem_4: 'option__4',
                },
                {
                    subitem_1: 'option__5',
                    subitem_2: 'option__6',
                    subitem_3: 'option__7',
                    subitem_4: 'option__8',
                },
                {
                    subitem_1: 'option__9',
                    subitem_2: 'option__10',
                    subitem_3: 'option__11',
                    subitem_4: 'option__12',
                }
            ]
        }
    }
}
</script>

<style scoped>
h1 {
    color: red;
}
</style>
