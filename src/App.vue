<script setup lang="ts">
import './assets/styles/global.scss'
import './assets/styles/style.scss'
import { RouterView } from 'vue-router'
import TopBar from './components/top-bar/TopBar.vue'
import Title from './components/title/Title.vue'
</script>

<template>
  <div class="left-bar">
    <Title name="notes" />
  </div>

  <TopBar />

  <RouterView />
</template>
