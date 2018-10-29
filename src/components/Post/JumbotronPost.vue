<template>
    <div class="jumbotron">
    <h1 class="display-5">
        <center>10</center>
        <center>TIPS KASFK</center>
        <center>ASFLAF</center>
        <center>ASFKLAFSK</center>
    </h1>
    <p class="lead mt-4">
        <a href="#"><i class="fas fa-caret-right" id="red"></i></a>&nbsp;&nbsp;&nbsp;
        <button class="my-custom-white-bt">TIPS HÄR</button>
    </p>
    </div>
</template>

<script>
export default {
    name: 'JumbotronPost'
}
</script>

<style scoped>

.jumbotron{
    font-family: 'Abril Fatface', cursive;
    border-radius: unset !important;
    background-color: rgb(193, 37, 35);
}

.my-custom-white-bt{
    color: rgb(216, 22, 20);
    background-color: white;
    width: 130px !important;
    height: 50px !important;
    font-family: 'Acme', sans-serif;
    font-size: 18px;
    letter-spacing: 1px;
    border-width: 0;    
    font-weight: 800;
}

center{
    color: white !important;
}

</style>

