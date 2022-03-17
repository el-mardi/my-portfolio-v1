<template>

  <div class="container">
     <h3  class="menuTitle"> 02. Some Things I have Built/></h3>
    <div class="projects">
      <Project  src="../assets/img/easybank.png" title = "EasyBank landing page" description= "Lorem ipsum dolor site consectetur adipisicing eli veniam Lorem ipsum dolor site consectetur adipisicing eli veniam " techs= "Html, Css, JavaScript" github="https://github.com/el-mardi/-Easybank--Responsive-Landing-Page" live="https://my-easy-bank.netlify.app/"/>

       <Project  src="../assets/img/blog.png" title = "Blog landing page" description= "Lorem 2 ipsum dolor site consectetur adipisicing eli veniam" techs= "Html, Css and JavaScript" github="https://github.com/el-mardi/Blogr--Responsive-Landing-Page" live="https://el-mardi-blog.netlify.app/"/>

       <Project  src="../assets/img/portfolio.png" title = "my old Portfolio" description= "Lorem 2 ipsum dolor site consectetur adipisicing eli veniam" techs= "Html, Css, JavaScript and VueJs framework" github="https://github.com/el-mardi/Portfolio-with-vue-js-3" live="https://el-mardi.github.io/Portfolio-with-vue-js-3/"/>

       <Project  src="../assets/img/portfolio.png" title = "E-commerce" description= "Lorem 2 ipsum dolor site consectetur adipisicing eli veniam Ps: Not finished yet" techs= "Html, Css, JavaScript, Jquery, Ajax and Laravel framework" github="https://github.com/el-mardi/e-commerce" live="##"/>

      <Project  src="../assets/img/portfolio.png" title = "This Portfolio" description= "Lorem 2 ipsum dolor site consectetur adipisicing eli veniam" techs= "Html, Css, JavaScript and VueJs framework" github="" live=""/>

    </div>
  </div>
 
</template>

<script>
import Project from '@/components/Project.vue'
export default {
  components: {
    Project
  },
}
</script>

<style lang="scss" scoped src="@/assets/style/work.scss">

</style>