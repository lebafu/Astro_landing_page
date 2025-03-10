<template id="#technologies">
    <section class="py-12">
      <h2 class="text-4xl font-bold text-center">Tecnologías que he utilizado</h2>
      <ul class="mt-6 grid grid-cols-2 gap-4 sm:grid-cols-3 lg:grid-cols-4">
        <li v-for="tech in technologies" :key="tech" class="bg-blue-500 p-4 rounded-lg shadow-md text-center">
          <p class="font-semibold">{{ tech }}</p>
        </li>
      </ul>
    </section>
  </template>
  
  <script setup lang="ts">
  const technologies: string[] = [
    'PHP', 'Laravel', 'CodeIgniter', 'JavaScript', 'React', 'Next.js', 'Spring Boot', 'Java', 'C++', 'Python', 'TailwindCSS', 'Vue.js',
  ];
  </script>
  
  <style scoped>
    /* Estilos específicos del componente */
  </style>