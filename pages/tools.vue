<template>
  <div class="container">
    <div class="content">
      <button class="button--grey" @click="goToPrev()"> 👈 Go Back</button>
      <h2>Tools/Technologies Categories:</h2>
      <div class="links">
        <NuxtLink class="button--green" to="tools_tech/web_builder">Website Builders</NuxtLink>
        <NuxtLink class="button--green" to="tools_tech/ui_design">UI Design</NuxtLink>
        <NuxtLink class="button--green" to="tools_tech/illustrations">Illustrations/Icons/Images</NuxtLink>
        <NuxtLink class="button--green" to="tools_tech/animations">Animations</NuxtLink>
        <NuxtLink class="button--green" to="tools_tech/patterns">Patterns</NuxtLink>
        <NuxtLink class="button--green" to="tools_tech/colors">Colors</NuxtLink>
        <NuxtLink class="button--green" to="tools_tech/fonts">Fonts</NuxtLink>
        <NuxtLink class="button--green" to="tools_tech/mockups">Mockups</NuxtLink>
        <NuxtLink class="button--green" to="tools_tech/organization">Organization</NuxtLink>
        <NuxtLink class="button--green" to="tools_tech/inspiration">Inspiration</NuxtLink>
        <NuxtLink class="button--green" to="tools_tech/tools_list">Tools</NuxtLink>
        <NuxtLink class="button--green" to="tools_tech/resources">Resources</NuxtLink>

      </div>

    </div>
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