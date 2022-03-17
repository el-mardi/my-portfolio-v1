<template>
  <Logo  v-if="loading" id="loading"/>
  <div v-else  class="">
    <NavBar />
    <div>
      <Socialmedia />
      <Home />
      <about />
      <Work />
      <Blog />
      <Contact />
      <Footer />
    </div>
  </div>
  
</template>

<script>

import Home from '@/views/Home.vue'
import About from '@/views/About.vue'
import Work from '@/views/Work.vue'
import Blog from '@/views/Blog.vue'
import Contact from '@/views/Contact.vue'
import Footer from '@/views/Footer.vue'
import Socialmedia from '@/components/Socialmedia.vue'
import NavBar from '@/components/NavBar.vue'
import Logo from '@/components/Logo.vue'

export default {
   components: {
    NavBar,
    Socialmedia,
    Logo,
    About,
    Home,
    Work,
    Blog,
    Contact,
    Footer,
  },
  data() {
    return {
      loading: false,
      todo: ''
    };
  },
  async created () {
    document.title = "El Mardi Ayoub"
    this.loading = true
    try {
      setTimeout(() => this.loading = false, 2550);
    } catch (error) {
      this.loading = false
    }
  }
}

</script>

<style lang="scss" src="./assets/style/global.scss">
</style>
