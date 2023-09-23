<template>
    <NotionRenderer :blockMap="blockMap" fullPage />
  </template>
  
  <script lang="ts" setup>
  const { $notion } = useNuxtApp();
  
  // use Notion module to get Notion blocks from the API via a Notion pageId
  const { data: blockMap } = useAsyncData("page_nuxt", () =>
    $notion.getPageBlocks("47d8330d5d0340d19d4336e58215375c")
  );
  </script>
  
  <style>
  @import "vue-notion/src/styles.css"; /* optional Notion-like styles */
  </style>
  