<script setup lang="ts">
import { RouterLink } from 'vue-router'

</script>


<template>
    <header class="top-bar">
        <nav>
            <ul>
                <RouterLink to="/">Home</RouterLink>
        <RouterLink to="/about">About</RouterLink>
        <RouterLink to="/tasks">Tasks</RouterLink>
            </ul>
        </nav>
    </header>
</template>