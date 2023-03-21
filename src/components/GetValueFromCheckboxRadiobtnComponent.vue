<template>
<h1>Get Value From Checkbox Radiobtn Component </h1>
<h3>Checkboxes:</h3>
<label id="label_1" for="option_1">Option 1</label>
<input type="checkbox" value="option 1" id="option_1" v-model="checkboxes" />
<br />
<label id="label_2" for="option_2">Option 2</label>
<input type="checkbox" value="option 2" id="option_2" v-model="checkboxes" />
<br />
<label id="label_3" for="option_3">Option 3</label>
<input type="checkbox" value="option 3" id="option_3" v-model="checkboxes" />
<h4>Checkboxes that selected: {{ checkboxes }}</h4>
<br /><br /><br />
<h3>Radiobuttons:</h3>
<label id="label_4" for="option_4">Option 4</label>
<input type="radio" value="option 4" id="option_4" v-model="radiobtns" name="radiobtn" />
<br />
<label id="label_5" for="option_5">Option 5</label>
<input type="radio" value="option 5" id="option_5" v-model="radiobtns" name="radiobtn" />
<br />
<label id="label_6" for="option_6">Option 6</label>
<input type="radio" value="option 6" id="option_6" v-model="radiobtns" name="radiobtn" />
<h4>Radiobtns that selected: {{ radiobtns }}</h4>
</template>

<script>
export default {
    name: 'GetValueFromCheckboxRadiobtnComponent',
    data() {
        return {
            checkboxes: [],
            radiobtns: null
        }
    }
}
</script>

<style scoped>
h1 {
    color: darkblue;
}
</style>
