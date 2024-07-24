<script setup>
import TheHeader from './components/TheHeader.vue';
import TheHome from './components/TheHome.vue';
import TheAbout from './components/TheAbout.vue';
import TheCarusel from './components/TheCarusel.vue';
import TheForms from './components/TheForms.vue';
import TheDonats from './components/TheDonats.vue';
import TheFooter from './components/TheFooter.vue';
</script>

<template>
  <div class="bg-[url('./public/backgraund.webp')] w-full h-full bg-cover min-h-screen bg-no-repeat relative">
    <div class="container">
      <TheHeader/>
      <TheHome/>
      <TheAbout/>
    </div>
    <TheCarusel/>
    <div class="container">
      <TheForms/>
      <TheDonats/>
    </div>
    <TheFooter/>
  </div>
  <footer></footer>
</template>
