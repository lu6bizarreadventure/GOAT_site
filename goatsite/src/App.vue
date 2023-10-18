<script setup>
// export default {
//   name: 'App'
// }
import HeaderItem from '@/components/HeaderItem.vue';
import { RouterLink, RouterView } from 'vue-router'
import HomeView from './views/HomeView.vue'
</script>

<template>
  <HeaderItem></HeaderItem>
  <HomeView></HomeView>
</template>

<style>
</style>
