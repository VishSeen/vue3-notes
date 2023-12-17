<script setup lang="ts">
import { type UserPanelProps }from '../../types/Props';

const props = defineProps<UserPanelProps>();

</script>

<template>
    <div class="user-panel">
        <div class="user-name">
            {{ props.name }}
        </div>

        <div class="user-img">
            <img :src="props?.image?.src" :alt="props?.image?.altText">
        </div>
    </div>
</template>