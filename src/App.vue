<template>
    <div class="font-sans">
        <nav class="h-16 w-full shadow-sm bg-gradient-to-l from-blue-400 via-blue-500 to-blue-600 flex items-center">
            <h2 class="text-gray-300 ml-7 font-semibold">Em processo de desenvolvimento...</h2>
        </nav>
        <div class="h-screen w-full flex items-center justify-center">
            <img class="h-80 w-80 block" 
                 :src="background" alt="App development">
        </div>
    </div>
</template>
<script lang="ts">
import { defineComponent } from 'vue';
import { background } from '@/assets/images';

export default defineComponent({
    name: 'App',

    setup() {
        return { background };
    }
});
</script>
<style>
</style>
