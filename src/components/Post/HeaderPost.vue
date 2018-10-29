<template>
    <div class="row">
        <div class="col-md-2 pr-0">
            <div class="container-fluid bottom-align-text pr-0">
                <img class="header-images" src="../../assets/laurence-cruz-1094026-unsplash.jpg" alt="">
                <div class="card-body py-0 mt-3" id="postData">
                    <h6 class="text-uppercase card-title text-center pr-2 mb-0 font-weight-bold" style="font-size: 13px; font-family: 'Work Sans', sans-serif;">{{postSubTitle}}</h6>
                    <div class="left pr-2 pt-0 mb-1">
                        <p class="font-weight-bold text-center mb-0" style="font-size: 12px; line-height: 13px;">{{postPlace}}</p>
                        <p class="font-weight-light text-center mb-0" style="font-size: 11px; line-height: 12px;">{{postDate}}</p>
                        <p class="font-weight-light text-center mb-0" style="font-size: 11px; line-height: 12px;"><i>{{postTime}}</i>
                        <span class="font-weight-light" style="font-size: 12px;"><i>{{postStatus}}</i></span></p>
                        <div class="m-0 p-0 mt-3 text-center"><button class="my-white-button">FÖLJ</button></div>
                    </div>
                </div>
            </div>
        </div>
        <div class="col-md-10 pl-0">
            <div class="container pl-0 pb-2">
                <img class="img-fluid" src="../../assets/13.png" alt="Not Available">
            </div>
        </div>
        <div class="col">
            <h1 class="card-main-title">Dokumentärerna du<br>
inte får missa</h1>
            <hr>
        </div>
    </div>    
</template>
<script>
export default {
    name: 'HeaderPost',
    data() {
    return {
            postTitle: 'Dokumentärerna du inte får missa',
            postSubTitle: 'KULTUR',
            postPlace: 'Lowe Andersson',
            postDate: '12 SEPT',
            postTime: '13 MIN ',
            postStatus: 'LÄSNING'
        }
    }
}
</script>
<style scoped>
hr{
    margin-left: 2.5em !important;
    margin-right: 2.5em !important;
}
img.img-fluid{
    width: 90%;
    height: 90%;
}
.container{
    margin-top: 1.5em;
}
.row {
    position: relative;
}
.header-images{
width: 100px;
height: 100px;
max-width: 150px;
max-height: 150px;
border-radius: 50%;
}
.bottom-align-text {
position: absolute;
bottom: 0;
right: 0;
}
.my-white-button{
    color: white !important;
    background-color: rgb(216, 22, 20);
    width: 80px;
    height: 30px;
    font-family: 'Acme', sans-serif;
    font-size: 13px;
    letter-spacing: 1px;
    border: 1px solid white;
}
.card-main-title{
    font-family: -webkit-body;
    color: #000 !important;
    line-height: 50px;
    font-size: 56px;
    font-weight: 800;
    letter-spacing: -2px;        
}
</style>
