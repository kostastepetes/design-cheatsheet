<template>
  <div class="container">
    <div class="content">

      <button class="button--grey" @click="goToPrev()"> 👈 Go Back</button>

      <h2>Research & Concepts</h2>
      <div class="links">
        <NuxtLink class="button--green" to="research_concepts/basic_research">Basics of Research</NuxtLink>
        <NuxtLink class="button--green" to="research_concepts/linear_lateral">Linear Reasoning vs Lateral Thinking</NuxtLink>
        <NuxtLink class="button--green" to="research_concepts/visualization">Idea Visualization</NuxtLink>
        <NuxtLink class="button--green" to="research_concepts/scheduling">Scheduling, Organizing & Finalizing</NuxtLink>
        <NuxtLink class="button--green" to="research_concepts/methods_design">Methods of Design Research</NuxtLink>

      </div>

    </div>
    <footer>Developed & Curated by 
      <a target="_blank" href="https://kostastepetes.netlify.app/">Kostas Tepetes</a> ⚡
    </footer>
  </div>
</template>

<script>  
export default {      
  methods: {
    goToPrev() {
      this.$router.go(-1)
    }
  } 
}
  </script>