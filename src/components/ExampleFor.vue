<template>
<ul>
    <li v-for="countrie in countries" v-bind:key="countrie">{{ countrie.name }}</li>
</ul>
</template>
<script lang="ts" setup>
import {Ref,ref} from 'vue';
let countries2:Ref<Array<string>>= ref([
    'Spain','France','UK','Italy'
])
interface Icountry {
    code:string,
    name:string
}
let countries:Ref<Array<Icountry>>=ref([

    {
        code:'es',
        name:'Spain'
    },{
        code:'fr',
        name:'France'
    }
])


</script>
<style scoped>
</style>