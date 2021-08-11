<template>
    <!-- Section onde ficara a parte de publicações -->
    <section class="feed">
        <FeedPub /><!-- Aqui ficarão as publicações que serão destaque na página -->
        <MoreNews /> <!-- Aqui são as publicações que são mais antigas, ficarão ao lado direito -->
    </section>
</template>

<script>
//Importo meus componentes da pasta components, uso o @ para referênciar a pasta src.
import FeedPub from '@/components/FeedPub.vue';
import MoreNews from '@/components/MoreNews.vue';

export default {
    name: 'Feed',
    //Declaro que meu componente Feed poderá usar outros componentes
    components: {
        FeedPub,
        MoreNews
    }
}
</script>

<style scoped>
    /* 
        Dentro da classe feed, adiciono um espaço interno dentro da Div para que os itens não fiquem
        colados com a borda, digo que seu display será flex e o seu conteúdo terá um espaçamento igual
        a sua volta.
    */
    .feed {
        padding: 10px;
        display: flex;
        justify-content: space-evenly;
    }
</style>