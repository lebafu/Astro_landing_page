<template id="#projects">
    <section class="py-12 bg-gray-100 text-center">
      <h2 class="text-4xl font-bold">Proyectos en los que he trabajado</h2>
      <ul class="mt-6 space-y-4 max-w-4xl mx-auto">
        <li v-for="project in projects" :key="project.id" class="bg-custom-blue p-4 rounded-lg shadow-md">
          <h3 class="text-2xl font-semibold">{{ project.name }}</h3>
          <p class="text-lg">{{ project.description }}</p>
        </li>
      </ul>
    </section>
  </template>
  
  <script setup lang="ts">
  interface Project {
    id: number;
    name: string;
    description: string;
  }
  
  const projects: Project[] = [
    { id: 1, name: 'Chatbot con Botpress', description: 'Implementación de un chatbot para preguntas frecuentes.' },
    { id: 2, name: 'Sitio Web Constructora Malpo', description: 'Desarrollo del sitio web de Constructora Malpo usando Next.js y PHP.' },
    { id: 3, name: 'Plataforma de Tickets Interno', description: 'Desarrollo de un sistema de gestión de tickets para el departamento de informática.' },
  ];
  </script>
  
  <style scoped>
  /* Estilos específicos del componente */
  </style>