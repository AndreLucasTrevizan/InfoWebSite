<template>
    <div class="feed-pub">
        <Pub />
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
    .feed-pub {
        width: 70%;
        margin-right: 10px;
        border-radius: 5px;
    }
</style>