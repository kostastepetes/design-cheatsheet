<template>
    <div class="container">
      <div class="content">
      
        <button class="button--grey" @click="goToPrev()"> 👈 Go Back</button>
        <h2>Methods of Design Research</h2>
        <div class="links">
          <NuxtLink class="button--green" to="design_methods/user_interviews">User Interviews</NuxtLink>
          <NuxtLink class="button--green" to="design_methods/case_study">Case Study Design</NuxtLink>
          <NuxtLink class="button--green" to="design_methods/exploratory">Exploratory Design</NuxtLink>
          <NuxtLink class="button--green" to="design_methods/observational">Observational Research Design</NuxtLink>
          <NuxtLink class="button--green" to="design_methods/descriptive">Descriptive Research Design</NuxtLink>
          <NuxtLink class="button--green" to="design_methods/longitudinal">Longitudinal Studies</NuxtLink>
          <NuxtLink class="button--green" to="design_methods/surveys">Surveys & Questionnaires</NuxtLink>
          <NuxtLink class="button--green" to="design_methods/cardsorting">Card Sorting</NuxtLink>
          <NuxtLink class="button--green" to="design_methods/usability">Usability Testing</NuxtLink>
          <NuxtLink class="button--green" to="design_methods/contexual">Contextual Inquiry</NuxtLink>
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