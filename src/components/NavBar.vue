<template>
    <nav>
        <a href="/"> <img class="logo" src="../assets/img/logo.png" alt=""> </a>
        <div class="nemu">
            <ol >
                <li><a href="#about">About</a></li>
                <li><a href="#works">works</a></li>
                <li><a href="#blog">Blog</a></li>
                <li><a href="#contact">Contact</a></li>
               
            </ol>
            <a href="/pdf/resume.pdf" target="_blank" class="btn btn-sm">Resume</a>
        </div>
        <div class="humbarger close" ref="humbarger" @click="humbargerMenu()">
            <span></span>
            <span ref="span2"></span>
            <span></span>
        </div>
        <div class="mobileNavBar" ref="mobileNavBar">
        <ol  type="1">
             <li><a href="#about" @click="humbargerMenu()">About</a></li>
                <li><a href="#works" @click="humbargerMenu()">works</a></li>
                <li><a href="#blog" @click="humbargerMenu()">Blog</a></li>
                <li><a href="#contact" @click="humbargerMenu()">Contact</a></li>
                <a href="/pdf/resume.pdf" target="_blank" class="btn btn-sm">Resume</a>
                <Links/>
        </ol>
        </div>
    </nav>
        <div ref="overly" class="overly"></div>
</template>

<script>
import Links from './Links.vue'
export default {
    components:{
        Links,
    },
    methods: {
        humbargerMenu (){
            const humbarger = this.$refs.humbarger;
            const mobileNavBar = this.$refs.mobileNavBar;
            const overly = this.$refs.overly;


            humbarger.classList.toggle('open');
            humbarger.classList.toggle('close');

            if (!humbarger.classList.contains('open')) {
                mobileNavBar.classList.add('fade-out');
                mobileNavBar.classList.remove('fade-in');
                overly.classList.remove('fade-in');
                overly.classList.add('fade-out');
                document.body.classList.remove('noscroll')
            } else {
                mobileNavBar.classList.add('fade-in');
                mobileNavBar.classList.remove('fade-out');
                overly.classList.add('fade-in');
                overly.classList.remove('fade-out');
                document.body.classList.add('noscroll')
            
            }
        },

    }
}
</script>

<style lang="scss" scoped src="../assets/style/navbar.scss">

</style>