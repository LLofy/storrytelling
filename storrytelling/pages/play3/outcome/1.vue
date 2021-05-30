<template>
    <div class="container">
        <div class="hero-container">
            <img class="imagem" src="~/assets/images/outcome7.jpg" />
            <div class="text-container">
                <h1 class="header">Foge e liga para a polícia</h1>
                <p class="texto">Você informa a polícia o que aconteceu e passa a localização do laboratório. Chegando lá ela se depara com um sítio de produção de cocaína e prende todos os presentes. As evidências sugerem que você ainda pode estar em perigo, por este motivo a polícia lhe coloca no programa deproteção à testemunha e você sobrevive para vivenciar uma nova história.<b class="especial"> Parabéns, você ganhou!</b></p>
                <div id="foo" >
                    <Btn2/>
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
    .especial{
        font-size:20px;
    }

    .imagem {
        width: 100%;
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