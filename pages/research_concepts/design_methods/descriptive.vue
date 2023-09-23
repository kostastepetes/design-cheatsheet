<template>
    <NotionRenderer :blockMap="blockMap" fullPage />
  </template>
  
  <script lang="ts" setup>
  const { $notion } = useNuxtApp();
  
  // use Notion module to get Notion blocks from the API via a Notion pageId
  const { data: blockMap } = useAsyncData("page_nuxt", () =>
    $notion.getPageBlocks("9cc5a7bf7e8c4f32b6018e0cbf0cef8e")
  );
  </script>
  
  <style>
  @import "vue-notion/src/styles.css"; /* optional Notion-like styles */
  </style>
  