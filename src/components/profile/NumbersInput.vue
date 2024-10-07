<script lang="ts" setup></script>

<template>
    <label for="message" class="block mb-2 font-medium text-gray-900"
        >Впишите список номеров:</label
    >
    <textarea
        id="message"
        rows="4"
        class="block p-2.5 w-full h-48 resize-none text-sm text-gray-900 bg-gray-50 rounded-lg border border-gray-300 focus:ring-blue-500 focus:border-blue-500 dark:bg-gray-700 dark:border-gray-600 dark:placeholder-gray-400 dark:focus:ring-blue-500 dark:focus:border-blue-500"
        :placeholder="'+712345678910\n+712345678910'"
    ></textarea>
</template>
