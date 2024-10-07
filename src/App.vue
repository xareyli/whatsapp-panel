<script setup lang="ts">
import { RouterView } from 'vue-router'
import whatsappIcon from '@/assets/whatsappsvg.svg'
</script>

<template>
    <header class="bg-gray flex items-center h-20 text-white">
        <div class="mx-auto w-[1300px] px-8">
            <div class="text-lg flex justify-start items-center">
                <img :src="whatsappIcon" class="w-8 h-auto mr-4" />
                <span class="lg:text-lg text-base">WhatsApp Panel</span>
            </div>
        </div>
    </header>

    <RouterView />
</template>

<style lang="scss" scoped></style>
