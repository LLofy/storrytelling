<template>
    <div class="card">
    <NuxtLink to="/play3/outcome/3">
        <img class="imagem" src="~/assets/images/outcome9.jpg" />
        <h1 class="header">Mata o homem, pega a marreta e vai ao laboratório</h1>
    </NuxtLink>
    </div>
</template>

<script>
</script>

<style scoped>
    .card {
        position:absolute;
        width:350px;
        margin-top:-336px;
        margin-left:900px;
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
        color:black;
    }
    .header:hover{
        color: black;
    }
</style>