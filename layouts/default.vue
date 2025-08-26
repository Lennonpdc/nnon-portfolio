<template>
  <div class="flex flex-col min-h-screen">
    <!-- Navbar -->
    <header class="bg-white shadow-md fixed w-full z-50">
      <nav class="container mx-auto flex justify-between items-center py-4 px-6">
        <h1 class="font-bold text-lg">My Portfolio</h1>
        <ul class="flex gap-6">
          <li><a href="#about" class="hover:text-indigo-500">About</a></li>
          <li><a href="#projects" class="hover:text-indigo-500">Projects</a></li>
          <li><a href="#contact" class="hover:text-indigo-500">Contact</a></li>
        </ul>
      </nav>
    </header>

    <!-- Page Content -->
    <main class="flex-1 pt-20">
      <slot />
    </main>

    <!-- Footer -->
    <footer class="bg-gray-100 py-6 text-center">
      <p class="text-sm text-gray-600">© 2025 Your Name. All rights reserved.</p>
    </footer>
  </div>
</template>
