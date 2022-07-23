<template>

  <div class="container">
     <h3  id="works" class="menuTitle"> 02. Some Things I have Built/></h3>
    <div class="projects">

      <Project  src="/img/gest-DSR.png" title = "Web application for the management of services for nationals" description= "Web application for the management of services for nationals within Chamber of commerce, industry and services Draa-Tafilelt CCISDT" techs= "Laravel framework, Html, TailwindCss, JavaScript, Jquery, Ajax, ChartJs, " github="https://github.com/el-mardi/GestionDesServicesPourCCISDT" live="#"/>

       <Project  src="/img/ecommerce.png" title = "E-commerce" description= "E-commerce web application built with laravel 8, containe users interfaces and admins sides to control the app"  ps= "Not finished yet" techs= "Html, Css, JavaScript, Jquery, Ajax and Laravel framework" github="https://github.com/el-mardi/e-commerce" live="#"/>

        <Project  src="/img/personelPortfolio.png" title = "My personal portfolio" description= "My personal portfolio (Responsive)" techs= "Html, Scss and VueJs framework" github="https://github.com/el-mardi/e-commerce" live="#"/>

        <Project  src="/img/portfolio.png" title = "Portfolio" description= "A responsive portfolio that I built with vueJs, containe personal blog and form to contact with EmailJS" techs= "Html, Css, JavaScript and VueJs framework" github="https://github.com/el-mardi/Portfolio-with-vue-js-3" live="https://el-mardi.github.io/Portfolio-with-vue-js-3/"/>

      <!-- <Project  src="/img/easybank.png" title = "EasyBank landing page" description= "EasyBank is a simple landing page that I built  just for fun" techs= "Html, Css, JavaScript" github="https://github.com/el-mardi/-Easybank--Responsive-Landing-Page" live="https://my-easy-bank.netlify.app/"/> -->

       <Project  src="/img/blog.png" title = "Landing page" description= "A simple responsive landing page" techs= "Html, Css and JavaScript" github="https://github.com/el-mardi/Blogr--Responsive-Landing-Page" live="https://el-mardi-blog.netlify.app/"/>
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