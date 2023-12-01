<template>
    <h1>For loop</h1>
    <table border="1px">
        <tr>
            <th>Id</th>
            <th>name</th>
            <th>email</th>
        </tr>
        <tr v-for="user in users" :key="user.id">
        <td>{{ user.id }}</td>
        <td>{{ user.name }}</td>
        <td>{{ user.email }}</td>  
        </tr>
    </table>
</template>
<script>
export default{
    name:"ForLoop",
    data(){
        return{
            users:[
                {id:1,name:"peter",email:'peter@123test.com'},
                {id:2,name:"peter2",email:'peter@2123test.com'},
                {id:3,name:"peter3",email:'peter@3123test.com'},
                {id:4,name:"peter4",email:'peter@4123test.com'}
            ]
        }
    }
}

</script>