<script lang="ts" setup>
import NumbersInput from './NumbersInput.vue'
import QRInput from './QRInput.vue'
import LogWindow from './LogWindow.vue'
</script>

<template>
    <section class="p-6 flex-1">
        <div class="flex flex-col h-full">
            <div class="flex justify-between">
                <div class="flex-1 mr-20">
                    <NumbersInput />
                </div>

                <div class="flex-1">
                    <QRInput />
                </div>
            </div>

            <div class="mt-auto">
                <LogWindow />
            </div>
        </div>
    </section>
</template>
