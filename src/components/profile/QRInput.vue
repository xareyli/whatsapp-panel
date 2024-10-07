<script lang="ts" setup>
import QrcodeVue, { type ImageSettings } from 'qrcode.vue'
import whatsappIcon from '@/assets/whatsapp-qr.svg'
import { ref } from 'vue'

const imageSettings = ref<ImageSettings>({
    src: whatsappIcon,
    width: 70,
    height: 70,
    excavate: false
})
</script>

<template>
    <h4 class="text-2xl font-bold mb-5">Отсканируйте QR код, чтобы авторизовать профиль:</h4>

    <qrcode-vue
        value="2@QDXGwRD6Z1injXUdOimaIutv/961X6+BhZTg4f2JtXUAcvpsEuHjFLdt1JaeuqWz5PkRW+IgkvlQZs01R4oBKah7iyvpfv+UlU8=,+5qQonuUGtnhQQzQnnaMQdUOnd+iGxWaexakz87nuUs=,VC02vJOG1LBKvD+QGfoFSxoYLoF4mMOi+A/M8Zzf2Qw=,DcCqxXWiKB5qLW3B+8GqFJg4RVxK/3xyJCuUZDBOVGA=,1"
        :image-settings="imageSettings"
        :size="250"
    ></qrcode-vue>
</template>
