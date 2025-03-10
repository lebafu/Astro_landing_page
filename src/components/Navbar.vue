<template>
    <!-- Navbar -->
    <nav class="bg-blue-600 text-white fixed w-full top-0 left-0 z-10 shadow-lg">
      <div class="flex justify-between items-center px-6 py-4">
        <!-- Foto de perfil -->
        <img src="/yo.jpg" alt="Foto de Leonardo Bascuñan" class="w-16 h-16 rounded-full object-cover">

        <!-- Menú hamburguesa para móviles -->
        <button class="lg:hidden text-white" id="menu-btn">
          ☰
        </button>

        <!-- Menú de navegación -->
        <ul class="hidden lg:flex space-x-6" id="menu">
          <li><a href="/" class="hover:bg-blue-700 px-4 py-2 rounded">Inicio</a></li>
          <li><a href="#about" class="hover:bg-blue-700 px-4 py-2 rounded">Acerca de</a></li>
          <li><a href="#experience" class="hover:bg-blue-700 px-4 py-2 rounded">Experiencia</a></li>
          <li><a href="#projects" class="hover:bg-blue-700 px-4 py-2 rounded">Proyectos</a></li>
          <li><a href="#technologies" class="hover:bg-blue-700 px-4 py-2 rounded">Tecnologías</a></li>
          <li><a href="#education" class="hover:bg-blue-700 px-4 py-2 rounded">Educación</a></li>
        </ul>
      </div>

      <!-- Menú móvil desplegable -->
      <ul class="lg:hidden hidden flex-col space-y-4 text-center bg-blue-700 py-4" id="mobile-menu">
        <li><a href="/" class="block hover:bg-blue-800 px-4 py-2 rounded">Inicio</a></li>
        <li><a href="#about" class="block hover:bg-blue-800 px-4 py-2 rounded">Acerca de</a></li>
        <li><a href="#experience" class="block hover:bg-blue-800 px-4 py-2 rounded">Experiencia</a></li>
        <li><a href="#projects" class="block hover:bg-blue-800 px-4 py-2 rounded">Proyectos</a></li>
        <li><a href="#technologies" class="block hover:bg-blue-800 px-4 py-2 rounded">Tecnologías</a></li>
        <li><a href="#education" class="block hover:bg-blue-800 px-4 py-2 rounded">Educación</a></li>
      </ul>
    </nav>
</template>