<template>
    <header>
        <div class="title">
            <h1>InfoWebSite</h1>
        </div>
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
    .title h1{
        margin-bottom: 2vh;
    }

    .menu ul {
        display: flex;
    }

    .menu ul li {
        padding: 10px;
        margin: 0px 30px;
    }

    .menu ul li:hover {
        color: #1D1E20;
        text-decoration: underline;
        background-color: white;
        cursor: pointer;
        border-radius: 5px;
        transition: 0.2s;
    }
</style>