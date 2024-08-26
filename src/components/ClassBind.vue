<template>
    <p v-bind:class="{'danger' : hasError}">El mensaje se ha enviado satisfactoriamente</p>
</template>
<script lang="ts">
    import { defineComponent, handleError } from "vue";
    
    export default defineComponent ({
        name:'ClassBind',
        //composition api
        // setup(){
        //     let hasError =true;
        //     return {hasError}
        // }
        
        //option api
        data(){
            return{
                hasError:true
            }
        }
    })
</script>
<style>
.danger{
    color:red;
}
</style>