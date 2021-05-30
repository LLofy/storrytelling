<template>
    <div class=" container">
        <div class="text-container">                 
            <NuxtLink to="/"> <button class="button btn">Voltar Ao Início</button></NuxtLink>
        </div>


    </div>
</template>

<script>
    export default {
        
    }
</script>
<style scoped>
    .text-container {
        margin-top: 10px;
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
        margin-left:20%;
        margin-top:100px;
    }

    .button:hover {
        width: 21.5rem;
    }
</style>