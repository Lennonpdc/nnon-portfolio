<template>
  <div 
    v-if="isVisible" 
    class="fixed inset-0 z-50 flex items-center justify-center p-4"
    @click.self="closeModal"
  >
    <div class="absolute inset-0 bg-black bg-opacity-50 backdrop-blur-sm"></div>
    
    <div class="relative bg-white rounded-2xl shadow-2xl max-w-4xl w-full max-h-[90vh] overflow-hidden animate-modal-enter">
      <button 
        @click="closeModal"
        class="absolute top-4 right-4 z-10 w-8 h-8 bg-gray-100 hover:bg-gray-200 rounded-full flex items-center justify-center transition-colors duration-200"
      >
        <svg class="w-5 h-5 text-gray-600" fill="none" stroke="currentColor" viewBox="0 0 24 24">
          <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M6 18L18 6M6 6l12 12"/>
        </svg>
      </button>

      <div class="flex flex-col md:flex-row h-full">
        <div class="md:w-2/5 bg-gradient-to-br from-blue-50 to-indigo-100 p-8 flex flex-col items-center justify-center text-center">
          <div class="mb-6">
            <div class="relative">
              <img 
                src="/public/images/cat-lennon-dev-pxls.jpg" 
                alt="Lennon" 
                class="w-70 h-48 object-cover rounded-xl shadow-lg"
              />
              <div class="absolute inset-0 bg-gradient-to-t from-blue-900/20 to-transparent rounded-xl"></div>
            </div>
          </div>
          
          <div class="space-y-3">
            <h3 class="text-xl font-semibold text-gray-800">Let's Code Together! 🍋</h3>
            <p class="text-gray-600 text-sm leading-relaxed">
              I'm always excited to collaborate on new projects and discuss innovative solutions. 
              Whether it's a simple question or a complex project, I'd love to hear from you!
            </p>
            <div class="flex justify-center space-x-2 text-2xl">
              <span class="animate-bounce">💻</span>
              <span class="animate-bounce" style="animation-delay: 0.1s">🚀</span>
              <span class="animate-bounce" style="animation-delay: 0.2s">✨</span>
            </div>
          </div>
        </div>

        <div class="md:w-3/5 p-8 overflow-y-auto bg-blue-950">
          <div class="h-full flex flex-col">
            <div class="mb-8">
              <h2 class="text-3xl font-bold text-white mb-2">Get In Touch</h2>
              <p class="text-gray-300">Ready to start something amazing? Let's connect!</p>
            </div>

            <div class="space-y-6 flex-grow">
              <div class="bg-gray-50 rounded-xl p-6 hover:shadow-md transition-shadow duration-200">
                <div class="flex items-start space-x-4">
                  <div class="w-12 h-12 bg-red-100 rounded-full flex items-center justify-center flex-shrink-0">
                    <svg class="w-6 h-6 text-red-600" fill="currentColor" viewBox="0 0 20 20">
                      <path d="M2.003 5.884L10 9.882l7.997-3.998A2 2 0 0016 4H4a2 2 0 00-1.997 1.884z"/>
                      <path d="M18 8.118l-8 4-8-4V14a2 2 0 002 2h12a2 2 0 002-2V8.118z"/>
                    </svg>
                  </div>
                  <div class="flex-grow">
                    <h4 class="font-semibold text-gray-800 mb-1">Email</h4>
                    <p class="text-gray-600 text-sm mb-2">Drop me a line anytime</p>
                    <a href="mailto:lennon@example.com" class="text-red-600 hover:text-red-700 font-medium">
                      lennonpaulcabrera@gmail.com
                    </a>
                  </div>
                </div>
              </div>

              <div class="bg-gray-50 rounded-xl p-6 hover:shadow-md transition-shadow duration-200">
                <div class="flex items-start space-x-4">
                  <div class="w-12 h-12 bg-blue-100 rounded-full flex items-center justify-center flex-shrink-0">
                    <svg class="w-6 h-6 text-blue-600" fill="currentColor" viewBox="0 0 24 24">
                      <path d="M19 3A2 2 0 0 1 21 5v14a2 2 0 0 1-2 2H5a2 2 0 0 1-2-2V5a2 2 0 0 1 2-2h14m-9 14v-6H8v6h2m-1-7.2a1.2 1.2 0 1 0 0-2.4 1.2 1.2 0 0 0 0 2.4m8 7.2v-3.4c0-2-1-3-2.6-3-1.2 0-1.8.7-2.1 1.3V11H13v6h2v-3.2c0-.2 0-.4.1-.5.2-.3.5-.6 1-.6.7 0 1.1.5 1.1 1.4V17h2Z"/>
                    </svg>
                  </div>
                  <div class="flex-grow">
                    <h4 class="font-semibold text-gray-800 mb-1">LinkedIn</h4>
                    <p class="text-gray-600 text-sm mb-2">Connect professionally</p>
                    <a href="https://www.linkedin.com/in/lennonpauldcabrera/" target="_blank" class="text-blue-600 hover:text-blue-700 font-medium">
                      /in/Lennonpdc
                    </a>
                  </div>
                </div>
              </div>

              <div class="bg-gray-50 rounded-xl p-6 hover:shadow-md transition-shadow duration-200">
                <div class="flex items-start space-x-4">
                  <div class="w-12 h-12 bg-gray-100 rounded-full flex items-center justify-center flex-shrink-0">
                    <svg class="w-6 h-6 text-gray-800" fill="currentColor" viewBox="0 0 24 24">
                      <path d="M12 .3a12 12 0 0 0-3.8 23.4c.6.1.8-.3.8-.6v-2c-3.3.7-4-1.6-4-1.6-.5-1.2-1.2-1.6-1.2-1.6-1-.7.1-.7.1-.7 1.1.1 1.7 1.2 1.7 1.2 1 .1.6 2.2 3.7 1.6v-2.2c-2.6.5-3.3-1.2-3.3-1.2-.5-1.2-1.2-1.6-1.2-1.6-1-.7.1-.7.1-.7 1.1.1 1.7 1.2 1.7 1.2 1 .1.6 2.2 3.7 1.6v-2.2c-2.6.5-3.3-1.2-3.3-1.2"/>
                    </svg>
                  </div>
                  <div class="flex-grow">
                    <h4 class="font-semibold text-gray-800 mb-1">GitHub</h4>
                    <p class="text-gray-600 text-sm mb-2">Check out my repositories</p>
                    <a href="https://github.com/Lennonpdc" target="_blank" class="text-gray-800 hover:text-gray-900 font-medium">
                      /Lennonpdc
                    </a>
                  </div>
                </div>
              </div>

              <div class="bg-gray-50 rounded-xl p-6 hover:shadow-md transition-shadow duration-200">
                <div class="flex items-start space-x-4">
                  <div class="w-12 h-12 bg-green-100 rounded-full flex items-center justify-center flex-shrink-0">
                    <svg class="w-6 h-6 text-green-600" fill="none" stroke="currentColor" viewBox="0 0 24 24">
                      <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M3 5a2 2 0 012-2h3.28a1 1 0 01.948.684l1.498 4.493a1 1 0 01-.502 1.21l-2.257 1.13a11.042 11.042 0 005.516 5.516l1.13-2.257a1 1 0 011.21-.502l4.493 1.498a1 1 0 01.684.949V19a2 2 0 01-2 2h-1C9.716 21 3 14.284 3 6V5z"/>
                    </svg>
                  </div>
                  <div class="flex-grow">
                    <h4 class="font-semibold text-gray-800 mb-1">Mobile</h4>
                    <p class="text-gray-600 text-sm mb-2">Call or text me</p>
                    <a href="tel:+639123456789" class="text-green-600 hover:text-green-700 font-medium">
                      +63 976 072 1191
                    </a>
                  </div>
                </div>
              </div>
            </div>

            <div class="mt-8 pt-6 border-t border-gray-200 text-center">
              <p class="text-gray-300 text-sm">
                I usually respond within 24 hours. Looking forward to hearing from you! 🍋
              </p>
            </div>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>

<script setup>
import { onMounted, onUnmounted } from 'vue'

// Define props
defineProps({
  isVisible: {
    type: Boolean,
    default: false
  }
})

// Define emits
const emit = defineEmits(['close'])

// Methods
const closeModal = () => {
  emit('close')
}

// Close modal on Escape key
const handleKeydown = (event) => {
  if (event.key === 'Escape') {
    closeModal()
  }
}

// Add event listener for Escape key when component mounts
onMounted(() => {
  document.addEventListener('keydown', handleKeydown)
})

// Remove event listener when component unmounts
onUnmounted(() => {
  document.removeEventListener('keydown', handleKeydown)
})
</script>

<style scoped>
/* Modal Animation */
.animate-modal-enter {
  animation: modalEnter 0.3s ease-out;
}

@keyframes modalEnter {
  from {
    opacity: 0;
    transform: scale(0.9) translateY(-20px);
  }
  to {
    opacity: 1;
    transform: scale(1) translateY(0);
  }
}

/* Custom Scrollbar for Contact Details */
.overflow-y-auto::-webkit-scrollbar {
  width: 6px;
}

.overflow-y-auto::-webkit-scrollbar-track {
  background: #f1f1f1;
  border-radius: 3px;
}

.overflow-y-auto::-webkit-scrollbar-thumb {
  background: #c1c1c1;
  border-radius: 3px;
}

.overflow-y-auto::-webkit-scrollbar-thumb:hover {
  background: #a1a1a1;
}
</style>