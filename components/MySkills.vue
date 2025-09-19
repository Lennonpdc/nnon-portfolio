<template>
    <section id="skills" class="min-h-screen flex flex-col justify-center items-center bg-gray-50 py-16">
        <h2 class="text-4xl font-bold mb-12 text-gray-800">Skills, Stacks, and Technologies</h2>

        <div class="max-w-6xl mx-auto grid grid-cols-1 md:grid-cols-2 lg:grid-cols-3 gap-8 px-4">
            <!-- Frontend Skills Card -->
            <div
                class="bg-slate-700 rounded-lg shadow-lg hover:shadow-xl transition-shadow duration-300 overflow-hidden">
                <!-- Header (Dark blue-gray background, white text) -->
                <div class="bg-slate-700 p-6 border-b border-slate-600">
                    <h3 class="text-xl font-semibold text-white">Frontend</h3>
                    <p class="text-slate-300 text-sm mt-1">User Interface & Experience</p>
                </div>

                <!-- Content (White background, dark text) -->
                <div class="bg-white p-6">
                    <div class="flex flex-wrap gap-2">
                        <span class="px-3 py-1 bg-green-100 text-green-800 rounded-full text-sm">Vue.js</span>
                        <span class="px-3 py-1 bg-blue-100 text-blue-800 rounded-full text-sm">Vuetify</span>
                        <span class="px-3 py-1 bg-pink-100 text-pink-800 rounded-full text-sm">Tailwind CSS</span>
                        <span class="px-3 py-1 bg-yellow-100 text-yellow-800 rounded-full text-sm">Pinia Store</span>
                        <span class="px-3 py-1 bg-green-100 text-green-800 rounded-full text-sm">Nuxt</span>
                        <span class="px-3 py-1 bg-orange-100 text-orange-800 rounded-full text-sm">HTML5</span>
                        <span class="px-3 py-1 bg-blue-100 text-blue-800 rounded-full text-sm">TypeScript</span>
                        <span class="px-3 py-1 bg-yellow-100 text-yellow-800 rounded-full text-sm">JavaScript</span>
                        <span class="px-3 py-1 bg-blue-100 text-blue-800 rounded-full text-sm">React.js</span>
                        <span class="px-3 py-1 bg-orange-100 text-orange-800 rounded-full text-sm">CSS</span>
                    </div>
                </div>
            </div>

            <!-- Backend Skills Card -->
            <div
                class="bg-slate-700 rounded-lg shadow-lg hover:shadow-xl transition-shadow duration-300 overflow-hidden">
                <div class="bg-slate-700 p-6 border-b border-slate-600">
                    <h3 class="text-xl font-semibold text-white">Backend</h3>
                    <p class="text-slate-300 text-sm mt-1">Server & Database</p>
                </div>

                <div class="bg-white p-6">
                    <div class="flex flex-wrap gap-2">
                        <span class="px-3 py-1 bg-green-100 text-green-800 rounded-full text-sm">Node.js</span>
                        <span class="px-3 py-1 bg-orange-100 text-orange-800 rounded-full text-sm">Laravel</span>
                        <span class="px-3 py-1 bg-blue-100 text-blue-800 rounded-full text-sm">Php</span>
                        <span class="px-3 py-1 bg-red-100 text-red-800 rounded-full text-sm">Nest.js</span>
                        <span class="px-3 py-1 bg-purple-100 text-purple-800 rounded-full text-sm">PostgreSQL</span>
                        <span class="px-3 py-1 bg-gray-100 text-gray-800 rounded-full text-sm">REST API</span>
                        <span class="px-3 py-1 bg-white text-white rounded-full text-sm">blank blank blank</span>
                    </div>
                </div>
            </div>

            <!-- Tools & Technologies Card -->
            <div
                class="bg-slate-700 rounded-lg shadow-lg hover:shadow-xl transition-shadow duration-300 overflow-hidden">
                <div class="bg-slate-700 p-6 border-b border-slate-600">
                    <h3 class="text-xl font-semibold text-white">Tools</h3>
                    <p class="text-slate-300 text-sm mt-1">Development & Deployment</p>
                </div>

                <div class="bg-white p-6">
                    <div class="flex flex-wrap gap-2">
                        <span class="px-3 py-1 bg-blue-100 text-blue-800 rounded-full text-sm">VS Code</span>
                        <span class="px-3 py-1 bg-orange-100 text-orange-800 rounded-full text-sm">GitHub</span>
                        <span class="px-3 py-1 bg-red-100 text-red-800 rounded-full text-sm">Figma</span>
                        <span class="px-3 py-1 bg-purple-100 text-purple-800 rounded-full text-sm">Insomnia</span>
                        <span class="px-3 py-1 bg-green-100 text-green-800 rounded-full text-sm">Vercel</span>
                        <span class="px-3 py-1 bg-yellow-100 text-yellow-800 rounded-full text-sm">Volta</span>
                        <span class="px-3 py-1 bg-purple-100 text-purple-800 rounded-full text-sm">Vite</span>
                        <span class="px-3 py-1 bg-gray-100 text-gray-800 rounded-full text-sm">Linux</span>
                    </div>
                </div>
            </div>
        </div>

        <div class="mt-16 w-full overflow-hidden bg-white py-8">
            <div class="flex animate-slide">
                <div class="flex items-center justify-center min-w-max">
                    <div class="flex items-center space-x-16 px-8">
                        <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/vuejs/vuejs-original.svg"
                            alt="Vue.js" class="w-12 h-12 opacity-60 hover:opacity-100 transition-opacity">
                        <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/nuxtjs/nuxtjs-original.svg"
                            alt="Nuxt.js" class="w-12 h-12 opacity-60 hover:opacity-100 transition-opacity">
                        <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/vuetify/vuetify-original.svg"
                            alt="Vuetify" class="w-12 h-12 opacity-60 hover:opacity-100 transition-opacity">
                        <img src="/public/icons/tailwind-css-svgrepo-com.png" alt="Tailwind CSS"
                            class="w-16 h-16 opacity-60 hover:opacity-100 transition-opacity">
                        <img src="/public/icons/pinia-logo.png" alt="Pinia Store"
                            class="w-12 h-12 opacity-60 hover:opacity-100 transition-opacity">
                        <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/typescript/typescript-original.svg"
                            alt="TypeScript" class="w-12 h-12 opacity-60 hover:opacity-100 transition-opacity">
                        <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/javascript/javascript-original.svg"
                            alt="JavaScript" class="w-12 h-12 opacity-60 hover:opacity-100 transition-opacity">
                        <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/github/github-original.svg"
                            alt="GitHub" class="w-12 h-12 opacity-60 hover:opacity-100 transition-opacity">
                        <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/nodejs/nodejs-original.svg"
                            alt="Node.js" class="w-12 h-12 opacity-60 hover:opacity-100 transition-opacity">
                        <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/vscode/vscode-original.svg"
                            alt="Visual Studio Code" class="w-12 h-12 opacity-60 hover:opacity-100 transition-opacity">
                        <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/insomnia/insomnia-original.svg"
                            alt="Insomnia" class="w-12 h-12 opacity-60 hover:opacity-100 transition-opacity">
                        <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/nestjs/nestjs-original.svg"
                            alt="NestJS" class="w-12 h-12 opacity-60 hover:opacity-100 transition-opacity">
                        <img src="/public/icons/vite-logo.png" alt="Vite"
                            class="w-12 h-12 opacity-60 hover:opacity-100 transition-opacity">
                        <img src="/public/icons/volta-logo.jpg" alt="Volta"
                            class="w-26 h-12 opacity-60 hover:opacity-100 transition-opacity">
                        <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/linux/linux-original.svg"
                            alt="Linux" class="w-12 h-12 opacity-60 hover:opacity-100 transition-opacity">
                        <img src="/public/icons/PostgreSQL_logo.png" alt="PostgreSQL"
                            class="w-12 h-12 opacity-60 hover:opacity-100 transition-opacity">
                        <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/react/react-original.svg"
                            alt="React.js" class="w-12 h-12 opacity-60 hover:opacity-100 transition-opacity">
                    </div>
                </div>
                <div class="flex items-center justify-center min-w-max">
                    <div class="flex items-center space-x-16 px-8">
                         <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/vuejs/vuejs-original.svg"
                            alt="Vue.js" class="w-12 h-12 opacity-60 hover:opacity-100 transition-opacity">
                        <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/nuxtjs/nuxtjs-original.svg"
                            alt="Nuxt.js" class="w-12 h-12 opacity-60 hover:opacity-100 transition-opacity">
                        <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/vuetify/vuetify-original.svg"
                            alt="Vuetify" class="w-12 h-12 opacity-60 hover:opacity-100 transition-opacity">
                        <img src="/public/icons/tailwind-css-svgrepo-com.png" alt="Tailwind CSS"
                            class="w-16 h-16 opacity-60 hover:opacity-100 transition-opacity">
                        <img src="/public/icons/pinia-logo.png" alt="Pinia Store"
                            class="w-12 h-12 opacity-60 hover:opacity-100 transition-opacity">
                        <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/typescript/typescript-original.svg"
                            alt="TypeScript" class="w-12 h-12 opacity-60 hover:opacity-100 transition-opacity">
                        <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/javascript/javascript-original.svg"
                            alt="JavaScript" class="w-12 h-12 opacity-60 hover:opacity-100 transition-opacity">
                        <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/github/github-original.svg"
                            alt="GitHub" class="w-12 h-12 opacity-60 hover:opacity-100 transition-opacity">
                        <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/nodejs/nodejs-original.svg"
                            alt="Node.js" class="w-12 h-12 opacity-60 hover:opacity-100 transition-opacity">
                        <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/vscode/vscode-original.svg"
                            alt="Visual Studio Code" class="w-12 h-12 opacity-60 hover:opacity-100 transition-opacity">
                        <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/insomnia/insomnia-original.svg"
                            alt="Insomnia" class="w-12 h-12 opacity-60 hover:opacity-100 transition-opacity">
                    </div>
                </div>
            </div>
        </div>
    </section>
</template>

<style scoped>
@keyframes slide {
    0% {
        transform: translateX(0);
    }

    100% {
        transform: translateX(-50%);
    }
}

.animate-slide {
    animation: slide 20s linear infinite;
}

.animate-slide:hover {
    animation-play-state: paused;
}
</style>