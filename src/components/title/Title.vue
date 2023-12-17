<script setup lang="ts">
import { TitleProps } from '../../types/Props';
import './style.scss'

const props = defineProps<TitleProps>();

</script>

<template>
    <div class="title-logo">
        <a :href="props.link" v-if="props.link">
            <span>
                {{ props.name }}
            </span>
        </a>

        <span v-else>
            {{ props.name }}
        </span>
    </div>
</template>