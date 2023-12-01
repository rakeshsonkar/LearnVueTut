<template>
  <h1>Hello Home  component {{msg}}</h1>  
  <p>
    {{data}}
  </p>
  <button v-on:click="hello('call para')">Call the function</button>
</template>

<script>
export default {
    name:'Home',
   props: {
    data:String,
    msg:String
    } ,
    methods:{
        hello(p){
           alert("hello console called " + p)
        }
    }
}
</script>