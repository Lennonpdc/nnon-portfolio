<template>
  <section id="projects" class="min-h-screen flex flex-col justify-center items-center bg-gray-50 py-16">
    <h2 class="text-4xl font-bold mb-12 text-gray-800">Projects Involved</h2>

    <div class="max-w-6xl mx-auto grid grid-cols-1 md:grid-cols-2 lg:grid-cols-3 gap-8 px-4">
      <!-- Experience Card 1 -->
      <div
        class="bg-white rounded-lg shadow-lg hover:shadow-xl hover:scale-105 transition-all duration-300 overflow-hidden">
        <!-- Header (White background, dark text) -->
        <div class="bg-white p-6 border-b border-gray-200">
          <h3 class="text-xl font-semibold text-gray-800">Frontend Developer</h3>
          <p class="text-gray-600 text-sm mt-1">Integrated Management System</p>
          <p class="text-gray-500 text-sm">2023 - Present</p>
        </div>

        <!-- Content (Dark blue-gray background, white text) -->
        <div class="bg-slate-700 p-6 text-white">
          <ul class="space-y-2 text-sm">
            <li>• Collaborated with a team to develop an Admission System to process the campus' online application</li>
            <li>• Assisted in the development of a Human Resource Management System that automated HR processes,
              improving efficiency</li>
            <li>• Contributed to the development of a Records Management System that automates processes and
              distribution of hardcopy documents across departments</li>
          </ul>
        </div>
      </div>

      <!-- Experience Card 2 -->
      <div
        class="bg-white rounded-lg shadow-lg hover:shadow-xl hover:scale-105 transition-all duration-300 overflow-hidden">
        <div class="bg-white p-6 border-b border-gray-200">
          <h3 class="text-xl font-semibold text-gray-800">UI/UX Developer</h3>
          <p class="text-gray-600 text-sm mt-1">Enrollment Management System</p>
          <p class="text-gray-500 text-sm">2022 - 2023</p>
        </div>

        <div class="bg-slate-700 p-6 text-white">
          <ul class="space-y-2 text-sm">
            <li>• Developed the complete UI/UX design for the Enrollment System</li>
            <li>• Created user-friendly interfaces to streamline the enrollment process</li>
            <li>• Ensured responsive design across different devices and screen sizes</li>
            <li>• Collaborated with stakeholders to understand user requirements and improve user experience</li>
          </ul>
        </div>
      </div>

      <!-- Experience Card 3 -->
      <div
        class="bg-white rounded-lg shadow-lg hover:shadow-xl hover:scale-105 transition-all duration-300 overflow-hidden">
        <div class="bg-white p-6 border-b border-gray-200">
          <h3 class="text-xl font-semibold text-gray-800">Freelance Project</h3>
          <div class="flex items-center gap-3 mt-1">
            <p class="text-gray-600 text-sm">Hyper X Cargo Inc.</p>
            <a href="https://www.hcliph.com/" target="_blank"
              class="flex items-center gap-1 text-xs font-medium text-green-600 hover:text-green-400 transition-colors duration-200">
              <span>Visit me</span>
              <svg class="w-3.5 h-3.5" fill="none" stroke="currentColor" viewBox="0 0 24 24" stroke-width="2.5">
                <path stroke-linecap="round" stroke-linejoin="round"
                  d="M13.5 6H5.25A2.25 2.25 0 003 8.25v10.5A2.25 2.25 0 005.25 21h10.5A2.25 2.25 0 0018 18.75V10.5m-10.5 6L21 3m0 0h-5.25M21 3v5.25" />
              </svg>
            </a>
          </div>
          <p class="text-gray-500 text-sm">January 2025 - March 2025</p>
        </div>

        <div class="bg-slate-700 p-6 text-white">
          <ul class="space-y-2 text-sm">
            <li>• Currently working on a custom web application for logistics management</li>
            <li>• Developing solutions to streamline cargo tracking and management processes</li>
            <li>• Working directly with client requirements to deliver tailored solutions</li>
            <li>• Implementing modern web technologies for optimal performance and user experience</li>
          </ul>
        </div>
      </div>
    </div>
  </section>
</template>