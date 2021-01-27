<template>
<div class="hello">
    <h3>Increment Counter</h3>
    <button @click="$store.dispatch('increment')">
        Press Me</button>
        <h5>Counter: {{$store.getters.counter}}</h5>
    </div>  
</template>

<script>
import Vue from "vue";

export default Vue.extend( {
    name: "Counter",
    props: {
        msg: String,
    },
    data:()=>({counter:0}),
});
</script>

<style>

</style>