<template>
  <!--Navigation Bar-->
  <nav class="navbar navbar-expand-lg bg-body-tertiary">
    <div class="container-fluid">
      <a class="navbar-brand" href="#">FITRI AMALIA</a>
      <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarNavAltMarkup" aria-controls="navbarNavAltMarkup" aria-expanded="false" aria-label="Toggle navigation">
        <span class="navbar-toggler-icon"></span>
      </button>
      <div class="collapse navbar-collapse" id="navbarNavAltMarkup">
        <div class="navbar-nav">
          <a class="nav-link active" aria-current="page"> <router-link to="/">Home</router-link></a>
          <a class="nav-link"> <router-link to="About">About</router-link></a>
        </div>
      </div>
    </div>
  </nav>

  <!--Router View-->
  <RouterView/>

</template>

<style scoped>

</style>
