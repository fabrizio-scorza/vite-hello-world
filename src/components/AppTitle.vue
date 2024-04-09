<script>

    export default{
        data(){
            return{
                title: 'La mia prima app con Vite!'
            }
        }
    }

</script>

<template>

    <h1 class="title">
        {{ title }}
    </h1>

</template>

<style>

    .title{
        text-align: center;
        padding: 10px;
        font-size: 48px;
        font-weight: 800;
        color: rgb(102, 118, 241);
    }
    
</style>