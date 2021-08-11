<template>
    <!-- Div feed-pub, é nela onde vão ser exibidas as publicações destaque -->
    <div class="feed-pub">
        <Pub /><!-- Componente responsável por renderizar os dados da publicação no feed -->
    </div>
</template>

<script>
import Pub from '@/components/Pub.vue';

export default {
    name: 'FeedPub',
    components: {
        Pub
    }
}
</script>

<style scoped>
    /*
     Digo que o component ocupará 70% da largura da Div pai, ou seja, da Div onde ele será posicionado.
     Terá uma margem na direita de 10 pixeis e a bora será aredondada.
    */
    .feed-pub {
        width: 70%;
        margin-right: 10px;
        border-radius: 5px;
    }
</style>