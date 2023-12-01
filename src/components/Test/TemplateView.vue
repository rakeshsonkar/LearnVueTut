<template>
  <p v-html="rowHtml"></p>
   <h2 v-once>{{ name }}</h2>
   <h2>{{ name }}</h2>
   <h3>{{ a+b }}</h3>
   <h4>{{ ok?"yes":"no" }}</h4>
   <button v-bind:disabled="disableBtn" v-on:click="updateText"> click me</button>
</template>

<script>
export default {
  name:'TemplateView',
    data(){
        return{
            name:'rakesh',
            a:10,
            b:20,
            ok:true,
            rowHtml:" <h1>Test the Templete  view</h1>",
            disableBtn:false
        }
    }
    ,methods:{
        updateText(){
            this.name="peter"
        }
    }
}
</script>