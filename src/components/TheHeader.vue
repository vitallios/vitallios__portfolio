<script setup>
import { RouterLink, RouterView } from 'vue-router'
</script>

<template>
 <div>
  <nav id="nav" class=" flex">
   <div class="" id="logo">
    <router-link to="/">V I T A L L I O S</router-link>
   </div>
   <ul class="" id="header__menu">
    <li>
     <RouterLink to="/">Home</RouterLink>
    </li>
    <li>
     <RouterLink to="/about">About</RouterLink>
    </li>
   </ul>
  </nav>
 </div>
</template>