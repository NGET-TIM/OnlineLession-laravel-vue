<template>
    <div>
        <Menu/>
        <h1 @click="clickMe()">Click Me</h1>
    </div>
</template>

<script>
    import Menu from './components/Menu'
    export default {
        components: {
            Menu,
        },
        
        data() {
            return {
                count: 0,
                users: [
                    { id: 0, name: 'Mr Jonh' },
                    { id: 1, name: 'Nget Tim' },
                    { id: 2, name: 'Mr Leap'}
                ]
            }
        },
        methods: {
            clickMe(m) {
                
            },

        },
        mounted() {
           
        },
        created() {
           
        },
    }
</script>

<style>

</style>
