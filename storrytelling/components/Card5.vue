<template>
    <div class="card">
    <NuxtLink to="/play2/outcome/2">
        <img class="imagem" src="~/assets/images/outcome5.jpg" />
        <h1 class="header">Pega o bilhete e foge para bem longe</h1>
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
        margin-left:520px;
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