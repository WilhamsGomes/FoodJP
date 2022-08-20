<template>
    <div class="conteudo">
        <h1>Mais populares</h1>
        <div class="pratos">
            <div class="prato">
                <img alt="Ramen de Frango" src="../assets/Prato01.png"/>
                <h3>Ramen de Frango</h3>
                <p>É uma das obsessões cá em casa no Inverno. Aquela deliciosa mistura de sopa com noodles, com o ovo mal cozido por cima, é verdadeiramente irresistível.</p>
                <span>R$30,99</span>
            </div>
            <div class="prato">
                <img alt="Ramen Apimentado" src="../assets/Prato02.png"/>
                <h3>Ramen Apimentado</h3>
                <p>É uma das obsessões cá em casa no Inverno. Aquela deliciosa mistura de sopa com noodles, com o ovo mal cozido por cima, é verdadeiramente irresistível.</p>
                <span>R$40,99</span>
            </div>
            <div class="prato">
                <img alt="Ramen Tradicional" src="../assets/Prato03.png"/>
                <h3>Ramen Tradicional</h3>
                <p>É uma das obsessões cá em casa no Inverno. Aquela deliciosa mistura de sopa com noodles, com o ovo mal cozido por cima, é verdadeiramente irresistível.</p>
                <span>R$28,99</span>
            </div>
        </div>
    </div>
</template>

<script>
    export default {
        name:"Populares"
    }
</script>

<style scoped>

.conteudo{
    margin-top: 70px;
    display: flex;
    align-items: center;
    flex-direction: column;
}

.pratos{
    display: flex;
    align-items: center;
    justify-content: center;
    margin-top: 180px;
}

.prato{
    background-color: #FBFBFB;
    height: 400px;
    width: 350px;
    border-radius: 15px;
    display: flex;
    align-items: center;
    justify-content: center;
    flex-direction: column;
    margin-left: 40px;
    margin-right: 40px;
}

.prato img{
    margin-top: -170px;
}

.prato h3{
    font-size: 25px;
    margin-top: 35px;
}

.prato p{
    font-size: 15px;
    color: rgb(145, 145, 145);
    text-align: justify;
    margin: 15px;
}

.prato span{
    font-size: 20px;
}

</style>