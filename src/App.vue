<script setup lang="ts">
import { RouterView } from 'vue-router'
import whatsappIcon from '@/assets/whatsappsvg.svg'
</script>

<template>
    <header class="bg-gray flex items-center h-20 text-white">
        <div class="mx-auto w-[1240px]">
            <div class="text-lg flex justify-start items-center">
                <img :src="whatsappIcon" class="w-8 h-auto mr-4" /> WhatsApp Panel
            </div>
        </div>
    </header>

    <RouterView />
</template>

<style lang="scss" scoped></style>
