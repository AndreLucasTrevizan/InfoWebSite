<template>
    <section class="feed">
        <FeedPub />
        <MoreNews />
    </section>
</template>

<script>
import FeedPub from '@/components/FeedPub.vue';
import MoreNews from '@/components/MoreNews.vue';

export default {
    name: 'Feed',
    components: {
        FeedPub,
        MoreNews
    }
}
</script>

<style scoped>
    .feed {
        padding: 10px;
        display: flex;
        justify-content: space-evenly;
    }
</style>