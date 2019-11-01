<style scoped>
    h1,h2 {font-weight: normal;}
</style>

<template>
    <h1>{{title}}</h1>

</template>

<script>
    import Vue from 'vue'
    export default Vue.extend({
        name: 'BookList',
        data() {
            return {
                title: 'All Books'
            }
        },
    })
</script>