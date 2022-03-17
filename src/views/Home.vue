<template>
  <div class="home container">
    <div class="content">
      <div class="title">
        <h2>
          <span class="hello">Hello 👋🏼 </span> My name is <span>El Mardi Ayoub, <br></span> 
              I enjoy <span>building</span> things for the <span>web</span>.
        </h2>
      </div>
      <div class="description">
        <p>
          I am a full-stack devoloper, I build things for the web. <br>
          I like to build accessible, inclusive products and automate processes and get things working behind the scenes.
        </p>
        <a href="#" target="_blank" class="btn btn-lg">Check out my Blog</a>
         <Links />
      </div>
    </div>
  </div>
</template>

<script>
// @ is an alias to /src
import Links from "../components/Links.vue";

export default {
  name: 'Home',
  components: {
    Links
  }
}
</script>

<style lang="scss" scoped src="@/assets/style/home.scss">

</style>