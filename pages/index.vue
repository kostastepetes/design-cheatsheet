<template>
  <div class="container">
    <Head>
            <Title>Design Cheatsheet - Design Resources and Theory Materials</Title>
         </Head>
    <div class="content">
      <img src="https://github.com/kostastepetes/design-cheatsheet/blob/17627c3ad77be05088ec039259af8af7d5d0a07b/public/Design%20Website%20Logo.png?raw=true" alt="design-cheatshett" width="150px"
        class="logo" />
      <h1>Design Cheatsheet</h1>
      <p>Welcome to Design Cheatsheet a crowdsourced collection of design resources and theory materials for design enthusiasts and professionals alike! Delve into the rich world of design theory, from color and design psychology to typography principles, empowering you to make informed, visually captivating choices. Unleash your design potential, enhance your knowledge, and stay inspired with our ever-growing repository of resources and insights.</p>

      <h3 class="nav">
        <span> · </span>
        <a target="_blank" href="https://design-cheatsheet.notion.site/design-cheatsheet/Design-Cheatsheet-9d8b7a6f920740c0aa2f447f46bc46aa">Docs</a>
        <span> · </span>
      </h3>

      <h2>Table of Contents:</h2>
      <div class="links">
        <NuxtLink class="button--green" to="/research">📊 Research & Concepts</NuxtLink>
        <NuxtLink class="button--green" to="/composition_concepts">📏 Composition</NuxtLink>
        <NuxtLink class="button--green" to="/typography">🆎 Typography</NuxtLink>
        <NuxtLink class="button--green" to="/color"> 🎨 Color Theory</NuxtLink>
        <NuxtLink class="button--green" to="/tools">🔨 Tools & Technologies</NuxtLink>
        <NuxtLink class="button--green" to="/web">💻 Web Design</NuxtLink>
        <NuxtLink class="button--green" to="/psychology">🧠 Design Psychology</NuxtLink>
        <NuxtLink class="button--green" to="/trends">📈 Design Trends</NuxtLink>
      </div>

    </div>
    <footer>Developed & Curated by 
      <a target="_blank" href="https://kostastepetes.netlify.app/">Kostas Tepetes</a> ⚡
    </footer>
  </div>
</template>

<script>
export default {
  head() {
    return {
      title: 'Design Cheatsheet - Design Resources and Theory Materials'
    }
  }
}
</script>