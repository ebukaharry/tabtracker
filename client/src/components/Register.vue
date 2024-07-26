<template>
    <div>
        <h1>Register</h1>

            <input type="email" name="email" placeholder="Enter Email..." v-model="email">
            <br>
            <input type="password" name="password" placeholder="Enter Password..." v-model="password">
            <br>
            <button @click="register">Submit</button>
    </div>
</template>
<script>
export default {
    data () {
        return {
            email: '',
            password: '',
        }
    },

    methods: {
        register () {
            console.log('hello', this.email, this.password)
        }
    },

}
</script>
<style >
    
</style>