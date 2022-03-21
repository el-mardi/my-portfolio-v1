<template>
    <nav>
        <a href="/"> <img class="logo" src="../assets/img/logo.png" alt=""> </a>
        <div class="nemu">
            <ol >
                <li><router-link to="#aboutme">About</router-link></li>
                <li><router-link to="/woks">works</router-link></li>
                <li><router-link to="/Blog">Blog</router-link></li>
                <li><router-link to="/contact">Contact</router-link></li>
               
            </ol>
            <a href="/pdf/resume.pdf" target="_blanck" class="btn btn-sm">Resume</a>
        </div>
        <div class="humbarger close" ref="humbarger" @click="humbargerMenu()">
            <span></span>
            <span ref="span2"></span>
            <span></span>
        </div>
        <div class="mobileNavBar" ref="mobileNavBar">
        <ol  type="1">
             <li><router-link to="#aboutme">About</router-link></li>
                <li><router-link to="/woks">works</router-link></li>
                <li><router-link to="/news">Blog</router-link></li>
                <li><router-link to="/contact">Contact</router-link></li>
        </ol>
        <a href="/pdf/resume.pdf" target="_blanck" class="btn btn-sm">Resume</a>
        </div>
    </nav>
        <div ref="overly" class="overly"></div>
</template>

<script>

export default {
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
        }
    }
}
</script>

<style lang="scss" scoped src="../assets/style/navbar.scss">

</style>