<template>
    <NotionRenderer :blockMap="blockMap" fullPage />
  </template>
  
  <script lang="ts" setup>
  const { $notion } = useNuxtApp();
  
  // use Notion module to get Notion blocks from the API via a Notion pageId
  const { data: blockMap } = useAsyncData("page_nuxt", () =>
    $notion.getPageBlocks("07b633d33a80414fb398c68aef04851c")
  );
  </script>
  
  <style>
  @import "vue-notion/src/styles.css"; /* optional Notion-like styles */
  </style>
  