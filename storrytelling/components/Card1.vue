<template>
    <div class="card">
    <NuxtLink to="/play1/outcome/1">
        <img class="imagem" src="~/assets/images/outcome1.jpg" />
        <h1 class="header">Corre o mais rápido possível</h1>
    </NuxtLink>
    </div>
</template>

<script>
</script>

<style scoped>
    .card {
        width:350px;
        margin-top:50px;
        margin-left:150px;
        border: none;
        overflow: hidden;
        cursor: pointer;
    }
    .imagem{
        width:300px;
        height: 300px;
    }
    .header {
        font-size: 1.15rem;
        margin-top: 0.4rem;
        margin-left:20px;
        color:black;
    }
    .header:hover{
        color: black;
    }
</style>