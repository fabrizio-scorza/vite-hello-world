<script>

    export default{
        data(){
            return{
                title:'a place to open your mind'
            }
        }
    }

</script>

<template>

    <div class="hero">
        <h1 class="hero__title">
        {{ title }}
        </h1>
    </div>
    
</template>

<style>

    .hero{        
        height: 550px;
        background-image: url('..\assets\hero.png');
        background-size: contain;
        background-position: center;
        background-repeat: no-repeat;
    }
    .hero__title{
        text-align:center;
        font-size: 24px;
        font-weight: 500;
        color: rgb(102, 118, 241);
    }
    
</style>