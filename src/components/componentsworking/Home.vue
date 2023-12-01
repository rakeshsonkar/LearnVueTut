<template>
    <div>
        <h1>Home component</h1> 
        <User />
        <Product />
        <Product />
    </div>
</template>
<script>
import User from './User.vue';
import Product from './products.vue';
export default{
   name:'Home',
   components:{
    User,
    Product
   }
}
</script>
<style  scoped>
div{
    background-color: #dde5ec;
    height: 100%;
}
</style>
