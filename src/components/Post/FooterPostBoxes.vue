<template>
    <div class="media m-3">
    <img class="img-fluid img-thumb" src="../../assets/11.png" alt="Card image cap">
    <div class="media-body pt-0 ml-4" id="postData">
        <h6 class="text-uppercase card-title left px-2 mb-0" style="font-size: 20px; line-height: 20px;">{{postSubTitle}}</h6>
        <div class="left px-2 pt-0 mb-1" style="line-height: 14px;">
            <span class="font-weight-bold" style="font-size: 13px; line-height: 14px;">{{postPlace}}</span>
            <br>
            <span class="font-weight-light" style="font-size: 12px; line-height: 13px;">{{postDate}}</span>
            <br>
            <span class="font-weight-light" style="font-size: 12px; line-height: 13px;"><i>{{postTime}}</i></span>
            <span class="font-weight-light" style="font-size: 12px; line-height: 13px;"><i>{{postStatus}}</i></span>
        </div>
        <p class="card-text left px-2"><label class="mb-0" style="font-weight: bold;">Här hittar du godaste <br>maten i NY</label><br>
        <label class="mb-0" style="font-family: 'Open Sans', sans-serif; font-weight: 500;"><i>Från colombianska arepas<br>
        i Queens till grekiskt i<br>
        Midtown och kinesiska<br>
        desserter i Brooklyn.<br>
        I New York finns smaker<br>
        från hela världen…</i></label><a href="#"><i class="fas fa-caret-right" id="black"></i></a></p>
    </div>
    </div>   
</template>

<script>
export default {
    name: 'FooterPostBoxes',
    data() {
    return {
            postSubTitle: 'MAT',
            postPlace: 'Carolina Granath ',
            postDate: '12 SEPT',
            postTime: '13 MIN ',
            postStatus: 'LÄSNING'
        }
    }
}

</script>

<style scoped>
    .img-thumb{
        width: 350px;
        height: 220px;
    }
p.card-text{
    font-size: 17px;
    line-height: 20px;
}   
</style>
