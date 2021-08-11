<template>
    <!-- Aqui declaro o header da aplicação -->
    <header>
        <!-- Classe para manipular o título mais tarde no CSS -->
        <div class="title">
            <h1>InfoWebSite</h1>
        </div>
        <!-- Div de navegação para o menu, com uma lista não ordenada -->
        <nav class="menu">
            <ul>
                <li>Sobre</li>
                <li>Noticias</li>
                <li>Classificados</li>
                <li>Contato</li>
            </ul>
        </nav>
    </header>
</template>

<script>
export default {
    name: 'Header'
}
</script>

<style scoped>
    /* Aqui digo que o título vai ter uma margem inferior de 2vh -> View Hate */
    .title h1{
        margin-bottom: 2vh;
    }

    /* Digo que a lista terá um display flex, assim os itens vão ser exibidos na vertical */
    .menu ul {
        display: flex;
    }

    /* Os itens da lista terão um espaço interno de 10 pixeis em cada lado e uma margem lateral de 30px */
    .menu ul li {
        padding: 10px;
        margin: 0px 30px;
    }

    /*
     hover indica que quando o cursos mouse passar por cima dos itens da lista, a cor do texto muda para preto
     fosco, será exibido um underline abaixo das letras e a cor de fundo será alterada para branco.
     O cursos vira um pointer, a bordar é arredondada e tudo será feito com uma transição de 0.2 segundos
    */
    .menu ul li:hover {
        color: #1D1E20;
        text-decoration: underline;
        background-color: white;
        cursor: pointer;
        border-radius: 5px;
        transition: 0.2s;
    }
</style>