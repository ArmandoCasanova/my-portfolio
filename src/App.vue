<template>
  <div class="min-h-screen bg-oscuro text-white font-poppins pt-24">
    <header class="fixed top-0 left-0 right-0 z-50">
      <div class="container mx-auto px-4 py-2">
        <div class="bg-gray-800 bg-opacity-50 backdrop-blur-md rounded-full shadow-lg px-8 py-4">
          <div class="flex justify-between items-center">
            <h1 class="text-xl font-bold tracking-wide">ARMANDO CASANOVA LEMUS</h1>
            <nav>
              <ul class="flex space-x-8 text-gray-300">
                <li><a href="#inicio" class="hover:text-white">SOBRE MI</a></li>
                <li><a href="#proyectos" class="hover:text-white">PROYECTOS</a></li>
                <li><a href="#educacion" class="hover:text-white">EDUCACION</a></li>
                <li><a href="#contacto" class="hover:text-white">CONTACTAME</a></li>
              </ul>
            </nav>
          </div>
        </div>
      </div>
    </header>

    <div class="relative">
      <div class="absolute inset-0 opacity-10"
        style="mask-image: linear-gradient(to bottom, black 60%, transparent 100%);">
        <img :src="codeImage" alt="Code background" class="w-full h-full object-cover blur-sm">
      </div>

      <div class="max-w-7xl mx-auto px-4">
        <section id="inicio" class="relative z-10 flex flex-col lg:flex-row items-center justify-between py-16 gap-8"
          data-aos="fade-up">
          <div class="flex-1 min-w-[320px]">
            <h2 class="text-3xl lg:text-6xl font-semibold mb-2">Hola<span class="text-cyan">!</span></h2>
            <h3 class="text-2xl lg:text-4xl font-light mb-2">Soy Armando</h3>
            <h4 class="text-3xl lg:text-6xl font-bold mb-6">Software Developer</h4>
            <div class="flex space-x-4 mb-8">
              <a href="#proyectos"
                class="bg-cyan text-white px-6 py-2 rounded-2xl hover:bg-opacity-90 transition-all duration-300 hover:scale-110 hover:shadow-[0_0_15px_rgba(0,191,255,0.8)] flex items-center justify-center">Mis Proyectos</a>
              <a href="#contacto"
                class="border border-cyan text-white px-6 py-2 rounded-2xl hover:bg-cyan transition-all duration-300 hover:scale-110 hover:shadow-[0_0_15px_rgba(0,191,255,0.8)] flex items-center justify-center">Contáctame</a>
            </div>
            <div class="flex space-x-4 mt-8">
              <a href="https://github.com/ArmandoCasanova" target="_blank"
                class="w-10 h-10 bg-transparent border-2 border-cyan rounded-full flex items-center justify-center text-cyan hover:bg-cyan hover:text-white hover:scale-110 hover:shadow-[0_0_15px_rgba(0,191,255,0.8)] transition-all duration-300">
                <svg xmlns="http://www.w3.org/2000/svg" width="20" height="20" viewBox="0 0 24 24" fill="none"
                  stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round">
                  <path
                    d="M9 19c-5 1.5-5-2.5-7-3m14 6v-3.87a3.37 3.37 0 0 0-.94-2.61c3.14-.35 6.44-1.54 6.44-7A5.44 5.44 0 0 0 20 4.77 5.07 5.07 0 0 0 19.91 1S18.73.65 16 2.48a13.38 13.38 0 0 0-7 0C6.27.65 5.09 1 5.09 1A5.07 5.07 0 0 0 5 4.77a5.44 5.44 0 0 0-1.5 3.78c0 5.42 3.3 6.61 6.44 7A3.37 3.37 0 0 0 9 18.13V22">
                  </path>
                </svg>
              </a>
              <a href="https://www.linkedin.com/in/armando-casanova-8680b2370" target="_blank"
                class="w-10 h-10 bg-transparent border-2 border-cyan rounded-full flex items-center justify-center text-cyan hover:bg-cyan hover:text-white hover:scale-110 hover:shadow-[0_0_15px_rgba(0,191,255,0.8)] transition-all duration-300">
                <svg xmlns="http://www.w3.org/2000/svg" width="20" height="20" viewBox="0 0 24 24" fill="none"
                  stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round">
                  <path d="M16 8a6 6 0 0 1 6 6v7h-4v-7a2 2 0 0 0-2-2 2 2 0 0 0-2 2v7h-4v-7a6 6 0 0 1 6-6z"></path>
                  <rect x="2" y="9" width="4" height="12"></rect>
                  <circle cx="4" cy="4" r="2"></circle>
                </svg>
              </a>
              <a href="mailto:armandocasanova005@gmail.com"
                class="w-10 h-10 bg-transparent border-2 border-cyan rounded-full flex items-center justify-center text-cyan hover:bg-cyan hover:text-white hover:scale-110 hover:shadow-[0_0_15px_rgba(0,191,255,0.8)] transition-all duration-300">
                <EnvelopeIcon class="w-5 h-5" />
              </a>
            </div>
          </div>
          <div class="flex-1 flex justify-center lg:justify-end mt-10 lg:mt-0">
            <div class="relative">
              <div class="absolute -inset-4 flex items-center justify-center">
                <div class="w-72 h-72 rounded-full bg-gradient-to-tr from-cyan to-transparent opacity-30"></div>
              </div>
              <img
                src="https://lh3.googleusercontent.com/pw/AP1GczOimrgfkSyGxhe4cKUBuaSVa6A28zauSaDqnaQJMsTCwfJSt4gs3Gz1lWrvcngZf4sPz_FDXRZcMYZPFX-_YhkcnZmp8ZDWiriMV5mPUAz-yRnL9VNRKcD2TK_I3Qh_82TXM1yRZt0Sav2H2xFXRC8=w713-h950-s-no-gm"
                alt="Profile" class="relative rounded-full w-64 h-64 object-cover border-4 border-cyan shadow-lg" />
            </div>
          </div>
        </section>

        <section id="sobre-mi"
          class="relative z-10 px-0 py-16 flex flex-col lg:flex-row items-start justify-between gap-8"
          data-aos="fade-up">
          <div class="flex-1 mb-10 md:mb-0">
            <div>
              <div class="space-y-12">
                <div class="flex items-center space-x-4 relative">
                  <div class="bg-oscuro border-2 border-cyan rounded-full p-2 z-10">
                    <ComputerDesktopIcon class="w-6 h-6 text-cyan" />
                  </div>
                  <span class="text-lg font-semibold">Desarrollo web</span>
                </div>
                <div class="flex items-center space-x-4 relative">
                  <div class="bg-oscuro border-2 border-cyan rounded-full p-2 z-10">
                    <DevicePhoneMobileIcon class="w-6 h-6 text-cyan" />
                  </div>
                  <span class="text-lg font-semibold">Desarrollo de apps móviles</span>
                </div>
                <div class="flex items-center space-x-4 relative">
                  <div class="bg-oscuro border-2 border-cyan rounded-full p-2 z-10">
                    <ServerIcon class="w-6 h-6 text-cyan" />
                  </div>
                  <span class="text-lg font-semibold">Bases de datos</span>
                </div>
              </div>
            </div>
          </div>
          <div class="flex-1">
            <p class="text-gray-300 text-lg mb-8">Soy un desarrollador de software, actualmente estudio la carrera de
              Ingeniería en Sistemas en el Instituto Tecnológico de Morelia, me apasiona la tecnología y el desarrollo
              de soluciones web o móviles, cuento con conocimientos variados en distintas tecnologías y me he adentrado
              en distintos proyectos que me han permitido ponerlos a prueba. Me considero alguien proactivo y que
              siempre esta en busca y disposición de aprender, me gusta crear soluciones eficientes y que cumplan los
              estándares, cuento con habilidades que me permiten pertenecer a distintos entornos de trabajo.</p>
          </div>
        </section>
      </div>
    </div>

    <TechStack data-aos="fade-up" />

    <div class="bg-black bg-opacity-20">
      <div class="max-w-7xl mx-auto px-4">
        <section id="proyectos" class="py-16" data-aos="fade-up">
          <h2 class="text-2xl md:text-3xl font-bold mb-8 text-center">Proyectos</h2>
          <swiper :slides-per-view="1" :space-between="30" :pagination="{ clickable: true }" :modules="modules">
            <swiper-slide v-for="(proyecto, index) in proyectos" :key="index" :class="proyecto.bgColor"
              class="rounded-3xl p-8">
              <div class="flex flex-col md:flex-row items-center">
                <div class="md:w-1/2 text-white">
                  <h3 class="text-3xl font-bold mb-4">{{ proyecto.title }}</h3>
                  <p>{{ proyecto.description }}</p>
                </div>
                <div class="md:w-1/2 mt-8 md:mt-0 md:pl-8">
                  <img :src="proyecto.image" alt="Project image" class="rounded-3xl shadow-lg">
                </div>
              </div>
            </swiper-slide>
          </swiper>
        </section>
        <section id="educacion" class="py-16" data-aos="fade-up">
          <h2 class="text-2xl md:text-3xl font-bold mb-8 text-center">Educación</h2>
          <div class="grid grid-cols-1 md:grid-cols-3 gap-8">
            <div
              class="bg-white bg-opacity-5 rounded-2xl shadow-lg p-6 flex flex-col items-center border-2 border-cyan transition-all duration-300 hover:scale-105 hover:shadow-[0_0_30px_0_rgba(0,191,255,0.5)]">
              <div
                class="w-20 h-20 mb-4 rounded-full border-2 border-cyan bg-white overflow-hidden flex items-center justify-center">
                <img src="/src/assets/images/tec.png" alt="ITM" class="w-full h-full object-cover" />
              </div>
              <h3 class="text-xl font-bold text-cyan mb-1 text-center">Ingeniería en Sistemas Computacionales</h3>
              <span class="text-gray-400 text-sm mb-2">2022 - Actualidad</span>
              <p class="text-gray-300 text-center">Instituto Tecnológico de Morelia. Formación en desarrollo de
                software, bases de datos, redes y gestión de proyectos tecnológicos.</p>
            </div>
            <div
              class="bg-white bg-opacity-5 rounded-2xl shadow-lg p-6 flex flex-col items-center border-2 border-cyan transition-all duration-300 hover:scale-105 hover:shadow-[0_0_30px_0_rgba(0,191,255,0.5)]">
              <div
                class="w-20 h-20 mb-4 rounded-full border-2 border-cyan bg-white overflow-hidden flex items-center justify-center">
                <img src="/src/assets/images/english.png" alt="english" class="w-full h-full object-cover" />
              </div>
              <h3 class="text-xl font-bold text-cyan mb-1 text-center">Inglés B2</h3>
              <span class="text-gray-400 text-sm mb-2">2019 - 2025</span>
              <p class="text-gray-300 text-center">Cursos y certificaciones de inglés en Instituto Tecnológico de
                Morelia. Impartición de docencia del idioma inglés por un año.</p>
            </div>
            <div
              class="bg-white bg-opacity-5 rounded-2xl shadow-lg p-6 flex flex-col items-center border-2 border-cyan transition-all duration-300 hover:scale-105 hover:shadow-[0_0_30px_0_rgba(0,191,255,0.5)]">
              <div
                class="w-20 h-20 mb-4 rounded-full border-2 border-cyan bg-white overflow-hidden flex items-center justify-center">
                <img src="/src/assets/images/coursera.png" alt="Coursera" class="w-full h-full object-cover" />
              </div>
              <h3 class="text-xl font-bold text-cyan mb-1 text-center">Certificación en Gestión de Proyectos</h3>
              <span class="text-gray-400 text-sm mb-2">2023</span>
              <p class="text-gray-300 text-center">Coursera. Certificado profesional en gestión de proyectos, abarcando
                metodologías ágiles y herramientas de planificación.</p>
            </div>
          </div>
        </section>
        <section id="contacto" class="py-16 flex flex-col items-center justify-center rounded-2xl bg-oscuro">
          <h2 class="text-4xl font-bold text-center mb-2">Contactame</h2>
          <p class="text-center text-gray-300 mb-8">Envíame un correo para entrar en contacto!</p>
          <div class="relative w-full max-w-xl mx-auto">
            <div class="absolute -top-8 -left-8 w-3/4 h-40 bg-cyan/20 rounded-2xl rotate-6"></div>
            <div class="absolute -bottom-8 -right-8 w-3/4 h-40 bg-cyan/20 rounded-2xl -rotate-6"></div>
            <form
              class="relative bg-white rounded-2xl shadow-lg p-8 z-10 border-4 border-cyan shadow-[0_0_30px_0_rgba(0,191,255,0.5)]">
              <label class="block text-black font-semibold mb-2" for="nombre">Nombre</label>
              <input id="nombre" type="text"
                class="w-full mb-4 px-4 py-2 rounded-lg border border-gray-300 text-black focus:outline-none focus:ring-2 focus:ring-cyan/40" />
              <label class="block text-black font-semibold mb-2" for="correo">Correo Electrónico</label>
              <input id="correo" type="email"
                class="w-full mb-4 px-4 py-2 rounded-lg border border-gray-300 text-black focus:outline-none focus:ring-2 focus:ring-cyan/40" />
              <label class="block text-black font-semibold mb-2" for="mensaje">Mensaje</label>
              <textarea id="mensaje" rows="4"
                class="w-full mb-6 px-4 py-2 rounded-lg border border-gray-300 text-black focus:outline-none focus:ring-2 focus:ring-cyan/40"
                placeholder="Cuéntame sobre tu proyecto, idea o vacante..."></textarea>
              <button type="submit"
                class="w-full flex items-center justify-center gap-2 bg-cyan text-white font-semibold px-6 py-3 rounded-lg hover:bg-opacity-90 transition-all duration-300 hover:scale-105 hover:shadow-[0_0_15px_rgba(0,191,255,0.8)]">
                <svg xmlns="http://www.w3.org/2000/svg" class="h-5 w-5" fill="none" viewBox="0 0 24 24"
                  stroke="currentColor">
                  <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M14 5l7 7m0 0l-7 7m7-7H3" />
                </svg>
                Enviar Mensaje
              </button>
            </form>
          </div>
        </section>
      </div>
    </div>
  </div>
</template>

<script setup>
import { ref, onMounted } from 'vue';
import { ComputerDesktopIcon, DevicePhoneMobileIcon, ServerIcon, EnvelopeIcon } from '@heroicons/vue/24/outline';
import { Swiper, SwiperSlide } from 'swiper/vue';
import 'swiper/css';
import 'swiper/css/pagination';
import { Pagination } from 'swiper/modules';
import nayaImage from './assets/images/naya.png';
import syncteamImage from './assets/images/syncteam.png';
import tailsUpImage from './assets/images/tails.png';
import codeImage from './assets/images/code4.png';
import AOS from 'aos';
import 'aos/dist/aos.css';
import TechStack from './components/TechStack.vue';

const proyectos = ref([
  {
    title: 'Nayá',
    description: 'Desarrollo de una aplicación multiplataforma para el aprendizaje emocional en niños, la cual contiene diferentes modulos praa padres, terapeutas y niños, como juegos, historietas interactivas, seguimiento y detección de patrones en respuestas emocionales.',
    image: nayaImage,
    bgColor: 'bg-pink-300 '
  },
  {
    title: 'SyncTeam',
    description: 'Desarrollo de una aplicación para la gestión de equipos de trabajo, que permite la colaboración en tiempo real, la asignación de tareas y el seguimiento del progreso de los proyectos.',
    image: syncteamImage,
    bgColor: 'bg-blue-500'
  },
  {
    title: 'TailsUp!',
    description: 'Desarrollo de una plataforma web tipo marketplace para la compra de productos y servicios para mascotas, que incluye funcionalidades como búsqueda avanzada, filtros, reseñas de usuarios y un sistema de pago seguro.',
    image: tailsUpImage,
    bgColor: 'bg-orange-500'
  }
]);

const modules = [Pagination];

onMounted(() => {
  AOS.init({
    duration: 900,
    once: false,
    easing: 'ease-out-cubic',
  });
});
</script>

<style>
@import url('https://fonts.googleapis.com/css2?family=Poppins:wght@300;400;500;600;700&display=swap');

.font-poppins {
  font-family: 'Poppins', sans-serif;
}

.swiper-pagination-bullet-active {
  background-color: white !important;
}

.swiper-slide {
  height: auto;
  display: flex;
  align-items: center;
  justify-content: center;
}
</style>