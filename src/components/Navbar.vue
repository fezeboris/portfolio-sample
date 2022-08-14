<template>
    <nav class="navbar navbar-expand-lg navbar-light bg-light">
  <div class="container-fluid">
    <a class="navbar-brand" href="#">TCHOUANFE</a>
    <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarNav" aria-controls="navbarNav" aria-expanded="false" aria-label="Toggle navigation">
      <span class="navbar-toggler-icon"></span>
    </button>
    <div class="collapse navbar-collapse" id="navbarNav">
      <ul class="navbar-nav">
        <li class="nav-item">
          <router-link class="nav-link active" aria-current="page" to="/">Home</router-link>
        </li>
        <li class="nav-item">
            <router-link class="nav-link" to="/projects"> projects</router-link>
        </li>
            <li class="nav-item">
              <router-link class="nav-link" to="/about">About </router-link>
            </li>
            <li class="nav-item">
              <router-link class="nav-link" to="/contact">Contact </router-link>
            </li>
        
      </ul>
    </div>
  </div>
</nav>
</template>

<script>
export default {
    setup () {
        

        return {}
    }
}
</script>

<style  scoped>
.navbar-brand{
    font-size: 2rem !important;
    font-weight: 600;
    /* font-family: 'Rubik Dirt', cursive; */
font-family: 'Rubik Distressed', cursive;
    color: grey;
}
.nav-link{
    font-size: 1.1rem;
    text-transform: uppercase;
}
.navbar-nav{
    margin-left: 15rem;
}
.nav-item{
    margin: 0px 15px;
    font-weight: 400;
}
</style>