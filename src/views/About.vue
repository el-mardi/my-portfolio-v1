<template>

  <div class="container">
     <h3 id="about"   class="menuTitle"> 01. About/></h3>
  <div class="about ">
    <div class="right">
        <img src="../assets/img/elmardiAyoub.png" alt="El Mardi Ayoub">
    </div>
    <div class="left">
      <div class="content">
        <p>
           <span class="hi">Hi 👋🏼</span>My name is EL Mardi Ayoub, I am a full-stack devoloper. specializing in building modern, resilient web application currently based in Morocco.
        </p>
        <p>
           
          I enjoy creating things for the web. My interst in web developpement started in 2018 <br>when I created basic web application with HTML CSS & PHP,<br>You can find samples of my work on my Github page, An example of my development work includes this portfolio, <br>and I will be adding other samples here in the future.
        </p>
        <p>
          Here are a few technologies I’ve been working with recently:
        </p>
        <div  class="tech_list">
          <ul>
            <li>Html</li>
            <li>Css</li>
            <li>JavaScript</li>
            <li>Php</li>
            <li>Ajax</li>
          </ul>
          <ul>
            <li>Laravel</li>
            <li>VueJs</li>
            <li>Bootstrap</li>
            <li>TailwinCss</li>
            <li>MySql</li>
          </ul>
        </div>
        <a href="http://github.com/el-mardi/" target="_blank" class="btn btn-lg">Check out my Github</a>
      </div>
    </div>
  </div>
  </div>
 
</template>

<script>
// @ is an alias to /src

export default {
  name: 'Home',
  components: {
  }
}
</script>

<style lang="scss" scoped src="@/assets/style/about.scss">

</style>