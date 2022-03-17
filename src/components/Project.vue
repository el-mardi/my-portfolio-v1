<template>
    <div class="project">
        <div class="img">
            <img src="../assets/img/blog.png" alt="">
            <div class="content">
            <a class="img-href" href="#">
                <div class="title">
                    <h1>{{title}}</h1>
                </div>
                <div class="description">
                    <p>{{description}}</p>

                    <div class="project-footer">
                       <p>Built with: {{techs}}</p>
                        <div class="links">
                            <a :href="github" target="_blank" id="github">
                                <svg xmlns="http://www.w3.org/2000/svg" role="img" viewBox="0 0 24 24" fill="none" stroke="#fff" stroke-width="2" stroke-linecap="round" stroke-linejoin="round" class="feather feather-github"><title>GitHub</title><path d="M9 19c-5 1.5-5-2.5-7-3m14 6v-3.87a3.37 3.37 0 0 0-.94-2.61c3.14-.35 6.44-1.54 6.44-7A5.44 5.44 0 0 0 20 4.77 5.07 5.07 0 0 0 19.91 1S18.73.65 16 2.48a13.38 13.38 0 0 0-7 0C6.27.65 5.09 1 5.09 1A5.07 5.07 0 0 0 5 4.77a5.44 5.44 0 0 0-1.5 3.78c0 5.42 3.3 6.61 6.44 7A3.37 3.37 0 0 0 9 18.13V22"></path></svg> GitHub
                            </a>

                            <a :href="live" target="_blank" id="live">
                                <svg xmlns="http://www.w3.org/2000/svg" role="img" viewBox="0 0 24 24" fill="none" stroke="#fff" stroke-width="2" stroke-linecap="round" stroke-linejoin="round" class="feather feather-external-link"><title>External Link</title><path d="M18 13v6a2 2 0 0 1-2 2H5a2 2 0 0 1-2-2V8a2 2 0 0 1 2-2h6"></path><polyline points="15 3 21 3 21 9"></polyline><line x1="10" y1="14" x2="21" y2="3"></line></svg> Live
                            </a>
                        </div>
                    </div>
                </div>
            </a>
        </div>
        </div>
    </div>  


    <!-- <div class="project">
        <div class="img">
            <img src="../assets/img/portfolio.png" alt="">
        </div>
        <div class="content">
            <a class="img-href" href="#">
                <div class="title">
                    <h3>{{title}}</h3>
                </div>
                <div class="description">
                    <p>{{description}}</p>

                    <div class="project-footer">
                       <p>Created with: {{techs}}</p>
                        <div class="links">
                            <a :href="github" target="_blank" class=" ">
                            <img src="../assets/img/github.svg" alt=""></a>

                            <a :href="live" target="_blank" class=" "><img src="../assets/img/link.png" alt=""></a>
                        </div>
                    </div>
                </div>
            </a>
        </div>
    </div>   -->
</template>

<script>
export default {
   
   props: ['src', 'title', 'description', 'techs', 'github', 'live']
}
</script>

<style lang="scss" scoped src="../assets/style/projet.scss">
    
</style>