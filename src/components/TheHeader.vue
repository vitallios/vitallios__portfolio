<script setup>
import { RouterLink } from 'vue-router'
</script>

<template>
 <header class=" py-4">
  <div class="container mx-auto px-2">
   <!-- Header -->
    <div class="flex justify-between items-center">
     <!-- Logo -->
     <div class="border rounded-md text-center p-3" id="logo">
      <router-link to="/">
       <h2 class="font-extrabold text-4xl">V I T A I I O S</h2>
       <div class="flex flex-row gap-6 pt-3 ">
        <span class="text-xs font-medium">W e b - d e s i g n</span>
        <span class="text-xs font-medium">F r o n t e n d - d e v e l o p e r</span>
       </div>
      </router-link>
     </div>
     <!-- Menu -->
     <nav id="header__menu" class="flex gap-4">
      <router-link to="/">Home</router-link>
      <router-link to="/skills">Skills</router-link>
      <router-link to="/portfolio">Portfolio</router-link>
     </nav>
    </div>
   <!-- Header -->
  </div>
 </header>
</template>