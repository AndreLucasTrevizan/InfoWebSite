<template>
  <div id="app">
    <Header />
    <Feed />
  </div>
</template>

<script>
import '@/style/style.css';
import Header from '@/components/Header.vue';
import Feed from '@/components/Feed.vue';

export default {
  name: 'App',
  components: {
    Header,
    Feed
  }
}
</script>

<style>

</style>