<template>
    <div class="container">
        <div class="hero-container">
            <img class="imagem" src="~/assets/images/outcome9.jpg" />
            <div class="text-container">
                <h1 class="header">Mata o homem, pega a marreta e vai ao laboratório</h1>
                <p class="texto">Você mata o homem, pega a marreta e se dirige ao laboratório. Ao avistar 2 guardas na entrada, confiante de si e seus feitos recentes, você corre na direção dos guardas, segurando a marreta com as duas mãos levantadas acima da sua cabeça e gritando “LEEROY JEENKINS!!!!”.Infelizmente, o efeito surpresa foi prejudicado e os guardas não tiveram dificuldade em alvejá-lo. Você morreu.</p>
                <div id="foo" >
                    <Btn1/>
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
        width: 150%;
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