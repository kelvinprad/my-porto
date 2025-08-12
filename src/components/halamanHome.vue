<template>
  <div
    class="flex flex-col min-h-[calc(100vh-96px)] items-center py-16 px-6 max-w-screen-lg mx-auto"
  >
    <!-- Bagian Atas: Profil -->
    <div class="flex flex-col items-center text-center gap-4">
      <h1 class="text-4xl font-bold">Hello, I am Kelvin Pradiza Lazuardy</h1>
      <p class="text-lg text-gray-300">
        I have a passion for beautiful interfaces, especially in UI/UX design.
      </p>
      <p class="text-lg text-gray-300">
        I am interested in learning more about frontend development.
      </p>
      <p class="text-lg text-gray-300">
        I enjoy learning new things and love taking on challenges.
      </p>
      <p class="text-lg text-gray-300">
        I am always looking for opportunities to grow and improve my skills.
      </p>

      <!-- Sosial Media -->
      <div class="flex gap-6 mt-4">
        <a
          href="https://www.instagram.com/kelvinpradiza"
          target="_blank"
          class="transition-colors duration-200 cursor-pointer"
        >
          <i class="fab fa-instagram text-4xl text-gray-400 hover:text-white"></i>
        </a>
        <a
          href="https://www.linkedin.com/in/kelvinpradiza/"
          target="_blank"
          class="transition-colors duration-200 cursor-pointer"
        >
          <i class="fab fa-linkedin text-4xl text-gray-400 hover:text-white"></i>
        </a>
        <a
          href="https://wa.me/628123456789"
          target="_blank"
          class="transition-colors duration-200 cursor-pointer"
        >
          <i class="fab fa-whatsapp text-4xl text-gray-400 hover:text-white"></i>
        </a>
      </div>
    </div>

    <!-- Bagian Skill -->
    <div class="w-full py-8 mt-8 sm:mt-10">
      <h2 class="text-2xl font-bold mb-6 text-center">Skills</h2>
      <div class="flex flex-wrap justify-center gap-6">
        <div
          class="bg-stone-800 rounded-2xl p-10 flex flex-col items-center justify-center gap-2 shadow-lg shadow-black/30 hover:shadow-xl hover:shadow-black/40 transition"
        >
          <i class="fab fa-python text-4xl text-yellow-400"></i>
          <p class="text-white font-normal">Python</p>
        </div>

        <div
          class="bg-stone-800 rounded-2xl p-10 flex flex-col items-center justify-center gap-2 shadow-lg shadow-black/30 hover:shadow-xl hover:shadow-black/40 transition"
        >
          <i class="fab fa-html5 text-4xl text-orange-500"></i>
          <p class="text-white font-normal">HTML</p>
        </div>

        <div
          class="bg-stone-800 rounded-2xl p-10 flex flex-col items-center justify-center gap-2 shadow-lg shadow-black/30 hover:shadow-xl hover:shadow-black/40 transition"
        >
          <i class="fab fa-css3-alt text-4xl text-blue-500"></i>
          <p class="text-white font-normal">CSS</p>
        </div>

        <div
          class="bg-stone-800 rounded-2xl p-10 flex flex-col items-center justify-center gap-2 shadow-lg shadow-black/30 hover:shadow-xl hover:shadow-black/40 transition"
        >
          <i class="fas fa-wind text-4xl text-blue-400"></i>
          <p class="text-white">Tailwind</p>
        </div>

        <div
          class="bg-stone-800 rounded-2xl p-10 flex flex-col items-center justify-center gap-2 shadow-lg shadow-black/30 hover:shadow-xl hover:shadow-black/40 transition"
        >
          <i class="fab fa-vuejs text-4xl text-green-500"></i>
          <p class="text-white font-normal">Vue.js</p>
        </div>

        <div
          class="bg-stone-800 rounded-2xl p-10 flex flex-col items-center justify-center gap-2 shadow-lg shadow-black/30 hover:shadow-xl hover:shadow-black/40 transition"
        >
          <i class="fab fa-bootstrap text-4xl text-purple-500"></i>
          <p class="text-white font-normal">Bootstrap</p>
        </div>

        <div
          class="bg-stone-800 rounded-2xl p-10 flex flex-col items-center justify-center gap-2 shadow-lg shadow-black/30 hover:shadow-xl hover:shadow-black/40 transition"
        >
          <i class="fas fa-magic text-4xl text-yellow-300"></i>
          <p class="text-white">Canva</p>
        </div>

        <div
          class="bg-stone-800 rounded-2xl p-10 flex flex-col items-center justify-center gap-2 shadow-lg shadow-black/30 hover:shadow-xl hover:shadow-black/40 transition"
        >
          <i class="fab fa-figma text-4xl text-pink-500"></i>
          <p class="text-white">Figma</p>
        </div>
      </div>
    </div>
  </div>
</template>

<script></script>
