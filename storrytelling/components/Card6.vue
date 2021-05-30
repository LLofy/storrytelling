<template>
    <div class="card">
    <NuxtLink to="/play2/outcome/3">
        <img class="imagem" src="~/assets/images/outcome6.jpg" />
        <h1 class="header">Puxa toda coragem do coração e enfrenta o homem</h1>
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