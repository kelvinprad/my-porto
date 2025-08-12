<template>
  <nav class="bg-stone-800 py-6">
    <ul class="flex justify-center gap-12 text-2xl font-semibold">
      <li>
        <button
          :class="[
            activePage === 'home' ? 'text-white' : 'text-gray-400 hover:text-white',
            'transition-colors duration-200 cursor-pointer',
          ]"
          @click="$emit('changePage', 'home')"
        >
          Home
        </button>
      </li>
      <li>
        <button
          :class="[
            activePage === 'profile' ? 'text-white' : 'text-gray-400 hover:text-white',
            'transition-colors duration-200 cursor-pointer',
          ]"
          @click="$emit('changePage', 'profile')"
        >
          Profile
        </button>
      </li>
      <li>
        <button
          :class="[
            activePage === 'project' ? 'text-white' : 'text-gray-400 hover:text-white',
            'transition-colors duration-200 cursor-pointer',
          ]"
          @click="$emit('changePage', 'project')"
        >
          Project
        </button>
      </li>
    </ul>
  </nav>
</template>

<script>
export default {
  name: 'tampilanNavbar',
  props: {
    activePage: {
      type: String,
      required: true,
    },
  },
}
</script>
