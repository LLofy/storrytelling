<template>
    <div class="Hero container">
        <div class="text-container">        
            <h1 class="header">Clique Abaixo Para Começar</h1>           
            <NuxtLink to="/play1"> <button class="button btn">Jogar</button></NuxtLink>            
        </div>


    </div>
</template>

<script>
    export default {
        
    }
</script>

<style scoped>
    .Hero {
        height: 550px;
        position: relative;
        top:1px;
        display: flex;
        padding: 20px 0;
        align-items: flex-start;
        justify-content: space-between;
    }

    .text-container {
        margin-top: 80px;
    }

    .header {
        font-weight: 900;
        font-size: 70px;
    }
     .button {
        align-content: center;
        padding: 1rem 4rem;
        border-radius: 100rem;
        background-color: rgb(231, 81, 43);
        color: white;
        width: 20rem;
        font-weight: 700;
        transition: 0.5s;
        margin-left:30%;
        margin-top:100px;
    }

    .button:hover {
        width: 21.5rem;
    }

    @media (max-width: 500px) {
        .Hero {
            height: 40vh;
        }
    }
</style>