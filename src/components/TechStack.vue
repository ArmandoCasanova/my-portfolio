<template>
  <div class="bg-oscuro py-16 sm:py-24">
    <div class="max-w-7xl mx-auto px-4">
        <h2 class="text-center text-2xl font-bold tracking-tight text-white sm:text-3xl mb-12">
            Tech Stack
        </h2>
        <div
            class="w-full inline-flex flex-nowrap overflow-hidden [mask-image:_linear-gradient(to_right,transparent_0,_black_128px,_black_calc(100%-128px),transparent_100%)]"
        >
            <ul class="flex items-center justify-center md:justify-start [&_li]:mx-4 animate-scroll-infinito">
                <li v-for="(tech, index) in conocimientos.concat(conocimientos)" :key="`tech1-${index}`" class="flex flex-col items-center justify-center gap-2 rounded-full bg-gray-800/90 border border-cyan/20 px-6 py-3 shadow-lg text-center">
                    <img :src="tech.logo" :alt="tech.name" class="h-10 w-10 mx-auto"/>
                    <span class="font-medium text-gray-300 mx-auto">{{ tech.name }}</span>
                </li>
            </ul>
            <ul class="flex items-center justify-center md:justify-start [&_li]:mx-4 animate-scroll-infinito" aria-hidden="true">
                <li v-for="(tech, index) in conocimientos.concat(conocimientos)" :key="`tech2-${index}`" class="flex flex-col items-center justify-center gap-2 rounded-full bg-gray-800/90 border border-cyan/20 px-6 py-3 shadow-lg text-center" aria-hidden="true">
                    <img :src="tech.logo" :alt="tech.name" class="h-10 w-10 mx-auto"/>
                    <span class="font-medium text-gray-300 mx-auto">{{ tech.name }}</span>
                </li>
            </ul>
        </div>
    </div>
  </div>
</template>

<script setup>
import { ref } from 'vue';

const conocimientos = ref([
  { name: 'Java', logo: 'https://www.vectorlogo.zone/logos/java/java-icon.svg' },
  { name: 'JavaScript', logo: 'https://www.vectorlogo.zone/logos/javascript/javascript-icon.svg' },
  { name: 'HTML', logo: 'https://www.vectorlogo.zone/logos/w3_html5/w3_html5-icon.svg' },
  { name: 'CSS', logo: 'https://www.vectorlogo.zone/logos/w3_css/w3_css-icon.svg' },
  { name: 'React', logo: 'https://www.vectorlogo.zone/logos/reactjs/reactjs-icon.svg' },
  { name: 'Tailwind', logo: 'https://www.vectorlogo.zone/logos/tailwindcss/tailwindcss-icon.svg' },
  { name: 'Python', logo: 'https://www.vectorlogo.zone/logos/python/python-icon.svg' },
  { name: 'Next.js', logo: 'https://www.vectorlogo.zone/logos/nextjs/nextjs-icon.svg' },
  { name: 'Docker', logo: 'https://www.vectorlogo.zone/logos/docker/docker-icon.svg' },
  { name: 'PostgreSQL', logo: 'https://www.vectorlogo.zone/logos/postgresql/postgresql-icon.svg' },
  { name: 'MySQL', logo: 'https://www.vectorlogo.zone/logos/mysql/mysql-icon.svg' },
  { name: 'Figma', logo: 'https://www.vectorlogo.zone/logos/figma/figma-icon.svg' },
  { name: 'Git', logo: 'https://www.vectorlogo.zone/logos/git-scm/git-scm-icon.svg' },
  { name: 'Vue', logo: 'https://www.vectorlogo.zone/logos/vuejs/vuejs-icon.svg' },
]);
</script>