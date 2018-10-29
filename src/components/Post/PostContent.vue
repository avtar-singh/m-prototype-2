<template>
    <div class="container-fluid">
        <HeaderPost/>
        <Content/>
        <FooterPost/>
    </div>
</template>

<script>
import HeaderPost from './HeaderPost'
import Content from './Content'
import FooterPost from './FooterPost'

export default {
    name: 'PostContent',
    components: {
        HeaderPost,
        Content,
        FooterPost
    }
}

</script>

<style scoped>
    hr { 
        display: block;
        margin-left: 1.5em;
        margin-right: 1.5em;
        border: 1px  #343a40 !important;
    }
    .dotted{
        border: none !important;
        border-radius: 0 !important;
        border-bottom: 1px dotted #343a40 !important;
        border-width: 0 2em;
    }
    .card-main-title{
        font-family: -webkit-body;
        color: #000;
        font-size: 50px;
        font-weight: 800;
        letter-spacing: -2px;        
    }
</style>
