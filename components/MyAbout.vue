<template>
  <section id="about" class="min-h-screen flex flex-col justify-center items-center bg-gray-50 py-16">

    <div class="max-w-4xl mx-auto px-4">
      <!-- Profile Picture -->
      <div class="flex justify-center mb-8">
        <div class="relative">
          <img src="/images/Lennon-Profile-Picture.jpg" alt="Lennon's Profile Picture"
            class="w-56 h-56 rounded-full object-cover shadow-xl border-4 border-white hover:scale-105 transition-transform duration-300" />
          <div class="absolute inset-0 rounded-full border-4 border-blue-800 opacity-30"></div>
        </div>
      </div>

      <!-- About Me Card -->
      <div class="bg-white rounded-2xl shadow-xl p-8 hover:shadow-2xl transition-shadow duration-300">
        <!-- Introduction -->
        <div class="text-center mb-8">
          <!-- <div ref="typingText" class="min-h-[120px]"> to update logic -->
          <h3 class="text-2xl font-semibold text-gray-800 mb-4">Hi, I'm Lennon! 🍋</h3>
          <p class="text-lg text-gray-600 leading-relaxed" id="typing-text">
            A passionate <span class="text-blue-800 font-medium">Full Stack Developer</span> with experience in
            building
            modern web applications.
            I love creating interactive and user-friendly digital experiences that make a difference.
          </p>
          <!-- </div> -->
        </div>
        <!-- Details Grid -->
        <div class="grid grid-cols-1 md:grid-cols-2 gap-8">
          <!-- Left Column -->
          <div class="space-y-6">
            <!-- Personal Info -->
            <div class="bg-gradient-to-r from-blue-50 to-indigo-50 p-6 rounded-xl">
              <h4 class="text-lg font-semibold text-gray-800 mb-4 flex items-center">
                <svg class="w-5 h-5 mr-2 text-blue-600" fill="currentColor" viewBox="0 0 20 20">
                  <path d="M10 9a3 3 0 100-6 3 3 0 000 6zm-7 9a7 7 0 1114 0H3z" />
                </svg>
                Personal Info
              </h4>
              <div class="space-y-3 text-sm">
                <div class="flex justify-between">
                  <span class="text-gray-600">Location:</span>
                  <span class="text-gray-800 font-medium">Malabon, Metro Manila, PH</span>
                </div>
                <div class="flex justify-between">
                  <span class="text-gray-600">Experience:</span>
                  <span class="text-gray-800 font-medium">3+ Years</span>
                </div>
                <div class="flex justify-between">
                  <span class="text-gray-600">Focus:</span>
                  <span class="text-gray-800 font-medium">Frontend Web Development</span>
                </div>
                <div class="flex justify-between">
                  <span class="text-gray-600">Status:</span>
                  <span class="text-green-600 font-medium">Open to Work (Remote/Hybrid)</span>
                </div>
              </div>
            </div>

            <!-- What I Do -->
            <div class="bg-gradient-to-r from-green-50 to-emerald-50 p-6 rounded-xl">
              <h4 class="text-lg font-semibold text-gray-800 mb-4 flex items-center">
                <svg class="w-5 h-5 mr-2 text-green-600" fill="currentColor" viewBox="0 0 20 20">
                  <path d="M9 12l2 2 4-4m6 2a9 9 0 11-18 0 9 9 0 0118 0z" />
                </svg>
                What I Do
              </h4>
              <ul class="space-y-2 text-sm text-gray-700">
                <li class="flex items-center">
                  <span class="w-2 h-2 bg-green-500 rounded-full mr-3"></span>
                  Frontend Development (Vue.js, Nuxt)
                </li>
                <!-- <li class="flex items-center">
                  <span class="w-2 h-2 bg-green-500 rounded-full mr-3"></span>
                  Backend Development (Node.js, Laravel)
                </li> -->
                <li class="flex items-center">
                  <span class="w-2 h-2 bg-green-500 rounded-full mr-3"></span>
                  UI/UX Design & Implementation
                </li>
                <li class="flex items-center">
                  <span class="w-2 h-2 bg-green-500 rounded-full mr-3"></span>
                  API Integration
                </li>
              </ul>
            </div>
          </div>

          <!-- Right Column -->
          <div class="space-y-6">
            <!-- Education -->
            <div class="bg-gradient-to-r from-purple-50 to-violet-50 p-6 rounded-xl">
              <h4 class="text-lg font-semibold text-gray-800 mb-4 flex items-center">
                <svg class="w-5 h-5 mr-2 text-purple-600" fill="currentColor" viewBox="0 0 20 20">
                  <path
                    d="M10.394 2.08a1 1 0 00-.788 0l-7 3a1 1 0 000 1.84L5.25 8.051a.999.999 0 01.356-.257l4-1.714a1 1 0 11.788 1.838L7.667 9.088l1.94.831a1 1 0 00.787 0l7-3a1 1 0 000-1.838l-7-3zM3.31 9.397L5 10.12v4.102a8.969 8.969 0 00-1.05-.174 1 1 0 01-.89-.89 11.115 11.115 0 01.25-3.762zM9.3 16.573A9.026 9.026 0 007 14.935v-3.957l1.818.78a3 3 0 002.364 0l5.508-2.361a11.026 11.026 0 01.25 3.762 1 1 0 01-.89.89 8.968 8.968 0 00-5.35 2.524 1 1 0 01-1.4 0zM6 18a1 1 0 001-1v-2.065a8.935 8.935 0 00-2-.712V17a1 1 0 001 1z" />
                </svg>
                Education
              </h4>
              <div class="space-y-3 text-sm">
                <div>
                  <h5 class="font-medium text-gray-800">BS Computer Engineering</h5>
                  <p class="text-gray-600">Polytechnic University of the Philippines</p>
                  <p class="text-gray-500 text-xs">2014 - 2020</p>
                </div>
              </div>
            </div>

            <!-- Interests -->
            <div class="bg-gradient-to-r from-orange-50 to-red-50 p-6 rounded-xl">
              <h4 class="text-lg font-semibold text-gray-800 mb-4 flex items-center">
                <svg class="w-5 h-5 mr-2 text-orange-600" fill="currentColor" viewBox="0 0 20 20">
                  <path
                    d="M3.172 5.172a4 4 0 015.656 0L10 6.343l1.172-1.171a4 4 0 115.656 5.656L10 17.657l-6.828-6.829a4 4 0 010-5.656z" />
                </svg>
                Interests
              </h4>
              <div class="flex flex-wrap gap-2">
                <span class="px-3 py-1 bg-orange-100 text-orange-800 rounded-full text-xs">Web Development</span>
                <span class="px-3 py-1 bg-red-100 text-red-800 rounded-full text-xs">UI/UX Design</span>
                <span class="px-3 py-1 bg-yellow-100 text-yellow-800 rounded-full text-xs">Open Source</span>
                <span class="px-3 py-1 bg-pink-100 text-pink-800 rounded-full text-xs">Technology</span>
                <span class="px-3 py-1 bg-indigo-100 text-indigo-800 rounded-full text-xs">Gaming</span>
                <span class="px-3 py-1 bg-green-100 text-green-800 rounded-full text-xs">Learning</span>
                <span class="px-3 py-1 bg-blue-100 text-blue-800 rounded-full text-xs">Basketball</span>

              </div>
            </div>

            <!-- Fun Fact -->
            <div class="bg-gradient-to-r from-cyan-50 to-blue-50 p-6 rounded-xl">
              <h4 class="text-lg font-semibold text-gray-800 mb-3 flex items-center">
                <svg class="w-5 h-5 mr-2 text-cyan-600" fill="currentColor" viewBox="0 0 20 20">
                  <path fill-rule="evenodd"
                    d="M18 10a8 8 0 11-16 0 8 8 0 0116 0zm-7-4a1 1 0 11-2 0 1 1 0 012 0zM9 9a1 1 0 000 2v3a1 1 0 001 1h1a1 1 0 100-2v-3a1 1 0 00-1-1H9z" />
                </svg>
                Fun Fact
              </h4>
              <p class="text-sm text-gray-700">
                I started coding during the pandemic and fell in love with creating digital solutions. Still learning
                backend development and new technologies.
                When I'm not coding, you'll find me exploring new technologies or playing games! 🎮
              </p>
            </div>
          </div>
        </div>

        <!-- Call to Action -->
        <div class="text-center mt-8 pt-6 border-t border-gray-200">
          <p class="text-gray-600 mb-4">Let's build something amazing together!</p>
          <div class="flex flex-wrap justify-center gap-4">
            <button @click="openContactModal"
              class="px-6 py-2 bg-blue-800 text-white rounded-lg hover:bg-blue-600 transition-colors duration-200 flex items-center">
              <svg class="w-4 h-4 mr-2" fill="currentColor" viewBox="0 0 20 20">
                <path d="M2.003 5.884L10 9.882l7.997-3.998A2 2 0 0016 4H4a2 2 0 00-1.997 1.884z" />
                <path d="M18 8.118l-8 4-8-4V14a2 2 0 002 2h12a2 2 0 002-2V8.118z" />
              </svg>
              Get In Touch
            </button>
            <a href="/cv/LennonPaulCabrera.pdf" download="LennonCabrera_CV.pdf"
              class="px-6 py-2 bg-green-700 text-white rounded-lg hover:bg-green-600 transition-colors duration-200 flex items-center">
              <svg class="w-4 h-4 mr-2" fill="currentColor" viewBox="0 0 20 20">
                <path fill-rule="evenodd"
                  d="M3 17a1 1 0 011-1h12a1 1 0 110 2H4a1 1 0 01-1-1zm3.293-7.707a1 1 0 011.414 0L9 10.586V3a1 1 0 112 0v7.586l1.293-1.293a1 1 0 111.414 1.414l-3 3a1 1 0 01-1.414 0l-3-3a1 1 0 010-1.414z" />
              </svg>
              Download CV
            </a>
            <a href="#projects"
              class="px-6 py-2 border border-gray-400 text-gray-700 rounded-lg hover:bg-gray-300 transition-colors duration-200 flex items-center">
              <svg class="w-4 h-4 mr-2" fill="currentColor" viewBox="0 0 20 20">
                <path fill-rule="evenodd"
                  d="M12.586 4.586a2 2 0 112.828 2.828l-3 3a2 2 0 01-2.828 0 1 1 0 00-1.414 1.414 4 4 0 005.656 0l3-3a4 4 0 00-5.656-5.656l-1.5 1.5a1 1 0 101.414 1.414l1.5-1.5zm-5 5a2 2 0 012.828 0 1 1 0 101.414-1.414 4 4 0 00-5.656 0l-3 3a4 4 0 105.656 5.656l1.5-1.5a1 1 0 10-1.414-1.414l-1.5 1.5a2 2 0 11-2.828-2.828l3-3z" />
              </svg>
              View Projects
            </a>
            <a href="https://my-blog-website-flame.vercel.app/login" target="blank"
              class="px-6 py-2 border bg-red-600 text-gray-200 rounded-lg hover:bg-red-400 transition-colors duration-200 flex items-center">
              <svg class="w-4 h-4 mr-2" fill="none" stroke="currentColor" viewBox="0 0 24 24" stroke-width="2">
                <path stroke-linecap="round" stroke-linejoin="round"
                  d="M12 6.042A8.967 8.967 0 006 3.75c-1.052 0-2.062.18-3 .512v14.25A8.987 8.987 0 016 18c2.305 0 4.408.867 6 2.292m0-14.25a8.966 8.966 0 016-2.292c1.052 0 2.062.18 3 .512v14.25A8.987 8.987 0 0018 18a8.967 8.967 0 00-6 2.292m0-14.25v14.25" />
              </svg>
              Personal Blog Site
            </a>
          </div>
        </div>
      </div>
    </div>
    <MyContact :isVisible="isContactModalVisible" @close="closeContactModal" />
  </section>
</template>

<script setup>
import { onMounted, nextTick, ref } from 'vue'
import MyContact from './MyContact.vue'

// Modal state
const isContactModalVisible = ref(false)

// Modal methods
const openContactModal = () => {
  console.log('Opening contact modal...') // Debug log
  isContactModalVisible.value = true
  console.log('isContactModalVisible:', isContactModalVisible.value) // Debug log
}

const closeContactModal = () => {
  console.log('Closing contact modal...') // Debug log
  isContactModalVisible.value = false
}

// Your existing typing animation code...
onMounted(async () => {
  await nextTick()

  const fullText = "A passionate Frontend Web Developer with experience in building modern web applications. I love creating interactive and user-friendly digital experiences that make a difference."

  let charIndex = 0
  const typingElement = document.getElementById('typing-text')

  console.log('Typing element found:', typingElement)

  if (!typingElement) {
    console.error('Typing element not found!')
    return
  }

  function typeWriter() {
    if (charIndex < fullText.length) {
      let currentText = fullText.substring(0, charIndex + 1)

      if (currentText.includes('Frontend Web Developer')) {
        currentText = currentText.replace(
          'Frontend Web Developer',
          '<span class="text-blue-800 font-medium">Frontend Web Developer</span>'
        )
      }

      typingElement.innerHTML = currentText
      charIndex++
      setTimeout(typeWriter, 50)
    } else {
      console.log('Typing animation completed!')
    }
  }

  console.log('Starting typing animation...')
  typeWriter()
})
</script>

<style scoped>
#typing-text::after {
  content: '|';
  animation: blink 1s infinite;
  color: #2563eb;
}

@keyframes blink {

  0%,
  50% {
    opacity: 1;
  }

  51%,
  100% {
    opacity: 0;
  }
}
</style>