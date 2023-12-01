<template>
    <h1 v-if="show">Conditional Rendering in vue  js</h1>
    <h1 v-else>Conditional Rendering in vue  js else</h1>
    <button v-on:click="display">toggle Element</button>
    
</template>

<script>
export default {
    name:"IFELSHIDESH",
    data(){
        return {show:false}
    },
    methods:{
       display(){
     
        this.show=!this.show
       } 
    }
}
</script>