<template>
    <NotionRenderer :blockMap="blockMap" fullPage />
  </template>
  
  <script lang="ts" setup>
  const { $notion } = useNuxtApp();
  
  // use Notion module to get Notion blocks from the API via a Notion pageId
  const { data: blockMap } = useAsyncData("page_nuxt", () =>
    $notion.getPageBlocks("2b9055f7059c47e9aa55ea9681f59174")
  );
  </script>
  
  <style>
  @import "vue-notion/src/styles.css"; /* optional Notion-like styles */
  </style>
  