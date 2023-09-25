<template>
  <div class="container">
    <div class="content">
      <button class="button--grey" @click="goToPrev()"> 👈 Go Back</button>
      <h2>Composition Concepts:</h2>
      <div class="links">
        <NuxtLink class="button--green" to="composition_theory/comp_basics">Basics Of Composition</NuxtLink>
        <NuxtLink class="button--green" to="composition_theory/form_space">Form & Space</NuxtLink>
        <NuxtLink class="button--green" to="composition_theory/symmetry">Symmetry/Asymmetry</NuxtLink>
        <NuxtLink class="button--green" to="composition_theory/layout_principles">Layout Principles</NuxtLink>
        <NuxtLink class="button--green" to="composition_theory/layout_styles">Styles of Layout</NuxtLink>
        <NuxtLink class="button--green" to="composition_theory/contrast">Contrast</NuxtLink>
        <NuxtLink class="button--green" to="composition_theory/size_format">Size & Format</NuxtLink>

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