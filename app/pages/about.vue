<!-- pages/index.vue -->
<template>
  <div>
    <h1>This is about page.</h1>
    <p>If you see this, Nuxt routing is working!</p>
  </div>
</template>

<script setup>
// Add meta tags and SEO settings
useHead({
  title: 'About | CreatelizeSwap',
  meta: [
    {
      name: 'description',
      content: 'This is the about page of CreatelizeSwap. Learn more about features and services.'
    },
    {
      name: 'keywords',
      content: 'createlize swap, about createlize, crypto swap Bangladesh'
    },
    {
      property: 'og:title',
      content: 'CreatelizeSwap - About Page'
    },
    {
      property: 'og:description',
      content: 'Learn more about the CreatelizeSwap platform.'
    },
    {
      property: 'og:type',
      content: 'website'
    }
  ]
})
</script>
