<template>
    <NotionRenderer :blockMap="blockMap" fullPage />
  </template>
  
  <script lang="ts" setup>
  const { $notion } = useNuxtApp();
  
  // use Notion module to get Notion blocks from the API via a Notion pageId
  const { data: blockMap } = useAsyncData("page_nuxt", () =>
    $notion.getPageBlocks("293ebdef0f1d435f8f31c7b9e922e9ff")
  );
  </script>
  
  <style>
  @import "vue-notion/src/styles.css"; /* optional Notion-like styles */
  </style>
  