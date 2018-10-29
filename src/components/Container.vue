<template>
    <div class="container-fluid">
        <PostContent/>
    </div>
</template>
<script>

import PostContent from './Post/PostContent';
// import PostBox from './PostBox'
// import Jumbotron from './Jumbotron'
// import PostTypes from './PostTypes'
// import Jumbotron2 from './Jumbotron2'
// import AdditionalData from './AdditionalData'
// import SubPostBox from './SubPostBox'

export default {
    name: 'Container',
    components: {
        PostContent,
        // PostBox,
        // Jumbotron,
        // PostTypes,
        // Jumbotron2,
        // AdditionalData,
        // SubPostBox
    }
}

</script>
<style>
body{
    margin: 2em !important;
    padding: 0;
    letter-spacing: 1.2px !important;
}
*{
    color:rgba(0,0,0,1) !important;
}
.my-centered-content{
  margin: auto;
}
.my-custom-right-border{
    border-right: 0.5px solid #343a40;
}

.my-custom-col-pad{
    padding-left: 0 !important;
}
/* .jumbotron-fluid{
    margin-left: 20px;
} */
hr{
    border: 0.5px solid #343a40 !important;
    /* margin-left: 20px; */
    font-weight: 300 !important;
    margin-bottom: 1rem !important;
}
#black{
    color: black !important;
}
.left{
    text-align: left;
}
.image{
    align-content: center;
    width: 100%;
    height: 200px !important;
}
p.card-text{
    text-align: justify;
    font-size: 20px;
    font-weight: 500;
    text-justify: inter-word;
    letter-spacing: 0.4px !important;
    line-height: 25px;
}
</style>
