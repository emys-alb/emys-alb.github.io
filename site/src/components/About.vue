<template>
    <div class="container">
        <div class="title">
            <h1>vou pedir licença para contar a minha história...</h1>
        </div>
        <div class="content">
            <p>Me chamo Emilly, sou natural de Campina Grande - PB, e faço graduação de Ciência da Computação na UFCG.</p>
            <p>Sou uma pessoa que coda até quando não tem que codar.</p>
            <p>Acredito que a tecnologia pode, e vem, mudando o mundo e o meu papel como desenvolvedora é usar meus conhecimentos para tornar o mundo um pouquinho melhor usando tecnologia.</p>
            <p>Além de ser claramente uma otimista, eu também sou obcecada por idiomas e sei falar inglês e francês.</p>
            <p>Sempre quero testar um hobby novo, como: edição de vídeos, crochê, andar de bicicleta, etc.</p>
        </div>
    </div>

</template>

<style scoped>
@import url('https://fonts.googleapis.com/css2?family=Libre+Baskerville:ital@0;1&display=swap');
.container {
    height: 100vh;
    display: flex;
    background-color: #F5F5F5;
    grid-template-columns: 1fr 1fr;
}

.title,
.content {
    padding: 25% 1em;
}


h1, p {
    color: #91b2d8;
    line-height: 1em;
    font-family: 'Libre Baskerville', serif;
    font-style: italic;
}
</style>