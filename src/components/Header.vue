<template>
  <div class="container-fluid">
    <div class="row m-2">
      <div class="col-lg-2 col-md-4">
          <img class="img-fluid" src="../assets/logo.png">
      </div>
      <div class="col-lg-7 col-md-6 my-centered-content">
        <SliderImages/>
      </div>
      <div class="col-lg-3 my-centered-content text-left">
        <div class="mt-1"><i class="fas fa-pencil-alt"></i><a class="text" href="#"> BLI MEDLEM</a></div>
        <div class="my-1"><i class="fas fa-unlock-alt"></i><a class="text" href="#"> LOGGA IN</a></div>
        <div class="mb-1"><i class="fas fa-search"></i><a class="text" href="#" style="color: red !important; text-decoration: none !important;"> SÖK</a></div>
      </div>
    </div>
    <div class="nav-rulers">
      <Navbar/>
    </div>
  </div>
</template>

<script>
  import SliderImages from './SliderImages'
  import Navbar from './Navbar'
  export default {
    name: 'Header',
    components: {
      SliderImages, Navbar
    },
    data() {
      return {
        msg: 'This is Header'
    }
  }
}

</script>
<style scoped>
label{
  margin-bottom: 0;
}
h1{
    color: slategray;
}
.nav-rulers{
  /* margin: 0 2em; */
  border-top: 1px solid #343a40;
  border-bottom: 1px solid #343a40;
}
</style>