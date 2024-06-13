<script setup>
import logo from './header_components/logo.vue'
import HeaderMenu from './header_components/menu.vue'
</script>

<template>
 <header class="py-4">
  <div class="container mx-auto px-2">
   <!-- Header -->
    <div class="flex justify-between items-center">
     <!-- Logo -->
     <logo/>
     <!-- Menu -->
     <HeaderMenu/>
    </div>
  </div>
 </header>
</template>