<template>
  <div class="min-h-screen bg-stone-800 text-white">
    <Navbar :activePage="currentPage" @changePage="currentPage = $event" />

    <main class="p-6 text-center">
      <Home v-if="currentPage === 'home'" />
      <Profile v-else-if="currentPage === 'profile'" />
      <Project v-else-if="currentPage === 'project'" />
    </main>
  </div>
</template>

<script>
import Navbar from './components/tampilanNavbar.vue'
import Home from './components/halamanHome.vue'
import Profile from './components/halamanProfile.vue'
import Project from './components/halamanProject.vue'

export default {
  components: { Navbar, Home, Profile, Project },
  data() {
    return {
      currentPage: 'home',
    }
  },
}
</script>
