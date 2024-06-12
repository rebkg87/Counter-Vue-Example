
<template>
    <div id="app">
        <h1> Contador: {{ counter }}</h1>
        <button @click="decrease"> - </button>
        <button @click="increase"> + </button>
    </div>
</template>

<script>
    export default {
        name: 'SimpleCounter',
        data() {
        return {
            counter: 0
        };
    },
    methods: {
        increase() {
            this.counter++;
        },
        decrease() {
            this.counter--;
        }
    }
};
</script>