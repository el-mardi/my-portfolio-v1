<template>
    <div class="container">
         <div class="footer">
         <Links />
            <a href="https://github.com/el-mardi" target="_blank" rel="noopener noreferrer"> Built with a lot of 💚 by El Mardi Ayoub ©️ 2022</a>
         </div>
    </div>        
</template>
<script>
import Links from "../components/Links.vue" ;
export default {
    components:{
        Links
    }
}
</script>
<style lang="scss" scoped>
@import '../assets/style/variables.scss';

.footer{

    padding: 0.5rem 0;
    a{
        text-decoration: none;
        text-align: center;
        letter-spacing: 0;
        font-family: $font-mono;
        font-size: $fz-xs;
        font-weight: 750;
        &:hover{
            color: $green;
    }
    }
}
</style>