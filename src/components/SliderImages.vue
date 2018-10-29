<template>
    <div class="container-fluid">
        <md-card-media>
          <!-- swiper -->
          <swiper :options="swiperOption">
            <swiper-slide>
              <div><img src="../assets/laurence-cruz-1094026-unsplash.jpg" alt="" class="img-responsive header-images"></div>
              <div><label class="my-centered-content">MIA<br>
SKÄRRINGER</label></div>              
            </swiper-slide>
            <swiper-slide>
              <div><img src="../assets/laurence-cruz-1094026-unsplash.jpg" alt="" class="img-responsive header-images"></div>
              <div><label class="my-centered-content">CAMILLA<br>
LÄCKBERG</label></div>  
            </swiper-slide>
            <swiper-slide>
              <div><img src="../assets/laurence-cruz-1094026-unsplash.jpg" alt="" class="img-responsive header-images"></div>
              <div><label class="my-centered-content">JONAS<br>
GARDELL</label></div>  
            </swiper-slide>
            <swiper-slide>
              <div><img src="../assets/laurence-cruz-1094026-unsplash.jpg" alt="" class="img-responsive header-images"></div>
              <div><label class="my-centered-content">LINNEA<br>
CARLSSON</label></div>  
            </swiper-slide>
            <swiper-slide>
              <div><img src="../assets/laurence-cruz-1094026-unsplash.jpg" alt="" class="img-responsive header-images"></div>
              <div><label class="my-centered-content">JAN<br>
GUILLOU</label></div>  
            </swiper-slide>
            <swiper-slide>
              <div><img src="../assets/laurence-cruz-1094026-unsplash.jpg" alt="" class="img-responsive header-images"></div>
              <div><label class="my-centered-content">Card</label></div>  
            </swiper-slide>
            <swiper-slide>
              <div><img src="../assets/laurence-cruz-1094026-unsplash.jpg" alt="" class="img-responsive header-images"></div>
              <div><label class="my-centered-content">Card</label></div>  
            </swiper-slide>
            <swiper-slide>
              <div><img src="../assets/laurence-cruz-1094026-unsplash.jpg" alt="" class="img-responsive header-images"></div>
              <div><label class="my-centered-content">Card</label></div>  
            </swiper-slide>
            <swiper-slide>
              <div><img src="../assets/laurence-cruz-1094026-unsplash.jpg" alt="" class="img-responsive header-images"></div>
              <div><label class="my-centered-content">Card</label></div>  
            </swiper-slide>
            <swiper-slide>
              <div><img src="../assets/laurence-cruz-1094026-unsplash.jpg" alt="" class="img-responsive header-images"></div>
              <div><label class="my-centered-content">Card</label></div>  
            </swiper-slide>
            <div class="swiper-pagination" slot="pagination"></div>
            <div class="swiper-button-prev" slot="button-prev"></div>
            <div class="swiper-button-next" slot="button-next"></div>
          </swiper>
        </md-card-media>
    </div>
</template>

<script>
  export default {
    name: 'SliderImages',
        data() {
            return {
            swiperOption: {
                slidesPerView: 5,
                spaceBetween: 10,
                slidesPerGroup: 5,
                loop: true,
                loopFillGroupWithBlank: true,
                pagination: {
                    el: '.swiper-pagination',
                    clickable: true
                },
                navigation: {
                    nextEl: '.swiper-button-next',
                    prevEl: '.swiper-button-prev'
                }
                }
            }
        }
    }
</script>

<style scoped>
.header-images{
  width: 100px;
  height: 100px;
  max-width: 150px;
  max-height: 150px;
  border-radius: 50%;
}
label{
    line-height: 15px;
    font-size: 12px;
}
a.nav-link{
  font-weight: 300 !important;
}
</style>