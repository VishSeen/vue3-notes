<script setup lang="ts">
  import './assets/styles/global.scss'
    import { RouterView } from 'vue-router'
    import TopBar from './components/top-bar/TopBar.vue'
    import UserPanel from './components/user-panel/UserPanel.vue';
    import Title from './components/title/Title.vue';
</script>

<template>

    <div class="left-bar">
        <Title name="Notes"/>
    </div>

    <TopBar />

    <UserPanel name="Vishroy seenarain" />

  <RouterView />
</template>