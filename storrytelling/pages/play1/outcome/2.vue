<template>
    <div class="container">
        <div class="hero-container">
            <img class="imagem" src="~/assets/images/outcome2.jpg" />
            <div class="text-container">
                <h1 class="header">Sobe na árvore</h1>
                <p class="texto">Você sobe na árvore e escapa por pouco da manada.</p>
                <div id="foo" >
                    <Btn12/>
                </div>
            </div>
        </div>
    </div>
</template>

<script>
</script>

<style scoped>
    .hero-container {
        margin-top:60px;
        display: flex;
        justify-content: space-between;
    }
    .text-container{
        margin-left:20px;
    }

    .imagem {
        width: 59%;
        height: 25rem;
    }
    h1 {
        left:100px;
        font-size: 1.75rem;
    }
    p {
        margin-top:100px;
        color: grey
    }
   
    button {
        width: 100%;
        border: none;
        color: white;
        font-weight: 700;
        border-radius: 100rem;
        background-color: rgb(231, 81, 43);
        color: white;
        font-weight: 700;
        transition: 0.5s;
    }
</style>