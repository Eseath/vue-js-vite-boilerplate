<template>
    <HelloWorld msg="Hello Vue 3 + TypeScript + Vite" />
</template>

<script lang="ts">
import { defineComponent } from 'vue';
import HelloWorld from './components/HelloWorld';

export default defineComponent({
    name: 'App',
    components: {
        HelloWorld,
    },
});
</script>
