<script setup lang="ts">
</script>

<template>
  <section id="contact" class="min-h-screen flex flex-col items-center justify-center bg-gray-200 p-10">
    <h2 class="text-4xl font-bold mb-4">Contact Me</h2>
    <form class="flex flex-col gap-4 w-full max-w-md">
      <input type="text" placeholder="Your Name" class="p-3 rounded border" />
      <input type="email" placeholder="Your Email" class="p-3 rounded border" />
      <textarea placeholder="Message" class="p-3 rounded border h-32"></textarea>
      <button class="bg-indigo-600 text-white px-6 py-3 rounded hover:bg-indigo-700">
        Send
      </button>
    </form>
  </section>
</template>
