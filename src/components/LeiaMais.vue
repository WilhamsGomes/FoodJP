<template>
    <div class="conteudo">
        <img src="../assets/imgComPrato.png">
        <div class="textos">
            <h1>Feita de forma tradicional</h1>
            <p>A comida tradicional japonesa é composta, principalmente, por arroz, peixe, sopas de missô, carne e picles, chamado de tsukemono no país. </p>
            <span>Ler mais sobre o modo de preparo</span>
        </div>
    </div>
</template>

<script>
export default {
    name:"LeiaMais"
}
</script>

<style scoped>

.conteudo{
    display: flex;
    align-items: center;
    justify-content:space-around;
    margin-left: 80px;
    margin-right: 160px;
}

.conteudo img{
    width: 450px;
}

.textos{
    margin-left: 50px;
}
.textos h1{
    font-size: 45px;;
    width: 350px;
    margin-bottom: 30px;
}
.textos p{
    text-align: justify;
    width: 450px;
    margin-bottom: 30px;
}

.textos span{
    color: #DA2535;
    text-decoration: underline
}

span:hover{
    cursor: pointer;
}

</style>