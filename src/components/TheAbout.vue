<script setup>
const skills = [
 {
  id: 'frontend1',
  title: '',
  img: 'src/assets/image/gurl.jpg',
  descrip: '',
 },
 {
  id: 'frontend2',
  title: '',
  img: 'src/assets/image/gurl.jpg',
  descrip: '',
 },
 {
  id: 'frontend3',
  title: '',
  img: 'src/assets/image/gurl.jpg',
  descrip: '',
 },
 {
  id: 'frontend4',
  title: '',
  img: 'src/assets/image/gurl.jpg',
  descrip: '',
 },
 {
  id: 'frontend5',
  title: '',
  img: 'src/assets/image/gurl.jpg',
  descrip: '',
 },

]
</script>
<template>
 <div id="about" class=" my-16">
  <ul class="grid grid-cols-4 grid-row-2  gap-5">
   <li 
   v-for="(item, i) of skills" 
   :key="item.id" 
   class="rounded  overflow-hidden h-[300px]"  
   :class="(`${i}` == '1' || `${i}` == '3' || `${i}` == 4) ? ' col-span-2' : ''"
   >
     <h2>{{ item.title }}</h2>
     <img :src=item.img alt="Image" class=" w-full h-full bg-cover object-cover">
     <p>{{ item.descrip }}</p>
   </li>
  </ul>
 </div>
</template>