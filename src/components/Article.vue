<template>
    <div class="article">
        <section class="content">
            <h3 class="Thetitle">
                {{title}}
            </h3>
            <p class="Thetext">
                {{text}}
            </p>
            <a :href="href" class="btn btn-lm" target="_blank" rel="noopener noreferrer">Learn More</a>
        </section>
    </div>        
</template>

<script>
export default {
    props: ['title', 'text', 'href']
}
</script>

<style lang="scss" src="../assets/style/articles.scss" scoped>
    
</style>