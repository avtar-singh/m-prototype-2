<template>
    <nav class="navbar navbar-expand-lg navbar-light bg-light">
    <button class="navbar-toggler" type="button" data-toggle="collapse" data-target="#navbarNav" aria-controls="navbarNav" aria-expanded="false" aria-label="Toggle navigation">
        <span class="navbar-toggler-icon"></span>
    </button>
    <div class="collapse navbar-collapse justify-content-md-center" id="navbarNav">
        <ul class="navbar-nav">
        <li class="nav-item active">
            <a class="nav-link" href="#">HEM/ TRÄDGÅRD<span class="sr-only">(current)</span></a>
        </li>
        <li class="nav-item">
            <a class="nav-link" href="#">KULTUR</a>
        </li>
        <li class="nav-item">
            <a class="nav-link" href="#">FÖRÄLDRASKAP</a>
        </li>
        <li class="nav-item">
            <a class="nav-link" href="#">LIVSSTIL</a>
        </li>
        <li class="nav-item">
            <a class="nav-link" href="#">POPULÄRT</a>
        </li>
        </ul>
    </div>
    </nav>
</template>

<script>
export default {
    name: 'Navbar'
}
</script>

<style scoped>
.nav-item{
  width: 200px;
}

nav{
    font-size: 1.3em;
}

.nav-link{
    text-decoration: none !important;
    text-transform: uppercase;
}

</style>

