<template>
  <div id="app">
    <nav id="nav" class="navbar navbar-expand-lg navbar-light bg-light">
      <a class="navbar-brand" href="/">
      <img src="@/assets/Logo2.png" alt="" height="80" class="d-inline-block align-text-top" loading="lazy" />
    </a>
   <button class="navbar-toggler"
    type="button"
    data-bs-toggle="collapse"
    data-bs-target="#navbarSupportedContent"
    aria-controls="navbarSupportedContent"
    aria-expanded="false"
    aria-label="Toggle navigation">
    <span class="navbar-toggler-icon"></span>
   </button>
<div class="collapse navbar-collapse" id="navbarSupportedContent">
  <ul class="navbar-nav mr-auto mt-2 mt-lg-0">
      <li class="nav-item">
        <router-link to="/" class="nav-link">Home</router-link>
        </li>
      <li class="nav-item">
        <router-link to="/uberuns" class="nav-link">Über uns</router-link>
        </li>
        <li class="nav-item">
        <router-link to="/kontakt" class="nav-link">Kontakt</router-link>
        </li>
  </ul>
  </div>

      </nav>
      
      <div class="container">
      <router-view/>
  </div>


  <!-- Footer -->
  <footer
          class="text-center text-lg-start text-white"
          style="background-color: #1c2331"
          >
    <!-- Section: Social media -->
    <section
             class="d-flex justify-content-between p-4"
             style="background-color: white"
             >
     
      <!-- Right -->
    </section>
    <!-- Section: Social media -->

    <!-- Section: Links  -->
    <section class="">
      <div class="container text-center text-md-start mt-5">
        <!-- Grid row -->
        <div class="row mt-3">
          <!-- Grid column -->
          <div class="col-md-3 col-lg-4 col-xl-3 mx-auto mb-4">
            <!-- Content -->
            <h6 class="text-uppercase fw-bold">DLL Metallbau GmbH</h6>
            <hr
                class="mb-4 mt-0 d-inline-block mx-auto"
                style="width: 60px; background-color: #7c4dff; height: 2px"
                />
            <p>
              
            </p>
          </div>
          <!-- Grid column -->

          <!-- Grid column -->
          <div class="col-md-2 col-lg-2 col-xl-2 mx-auto mb-4">
            
            <h6 class="text-uppercase fw-bold">Kontakt</h6>
            <hr
                class="mb-4 mt-0 d-inline-block mx-auto"
                style="width: 60px; background-color: #7c4dff; height: 2px"
                />
            <p><i class="fas fa-home mr-3"></i> Blumenrainstrasse 8 CH-6032 Emmen</p>
            <p><i class="fas fa-envelope mr-3"></i><a href="/kontakt" class="text-reset" style="text-decoration: none"> dalibor.jakovic@gmx.ch</a></p>
            <p><i class="fas fa-phone mr-3"></i> +41 76 788 62 46</p>
          </div>
          <!-- Grid column -->

          <!-- Grid column -->
          <div class="col-md-3 col-lg-2 col-xl-2 mx-auto mb-4">
            <!-- Links -->
            <h6 class="text-uppercase fw-bold">Unsere Dienstleistungen</h6>
            <hr
                class="mb-4 mt-0 d-inline-block mx-auto"
                style="width: 60px; background-color: #7c4dff; height: 2px"
                />
            <p>
              <i class="text-reset"><a href="/metallbau" class="text-reset" style="text-decoration: none">Metallbau</a></i>
            </p>
            <p>
              <i class="text-reset"><a href="/glasbau" class="text-reset" style="text-decoration: none">Glasbau</a></i>
            </p>
            <p>
              <i class="text-reset"><a href="/torbau" class="text-reset" style="text-decoration: none">Torbau</a></i>
            </p>
            <p>
              <i class="text-reset"><a href="/montagen" class="text-reset" style="text-decoration: none">Montagen</a></i>
            </p>
            <p>
              <i class="text-reset"><a href="/fenster" class="text-reset" style="text-decoration: none">Fenster</a></i>
            </p>
            <p>
              <i class="text-reset"><a href="/gelander" class="text-reset" style="text-decoration: none">Geländer</a></i>
            </p>
          </div>
          <!-- Grid column -->
          <!-- Grid column -->
        </div>
        <!-- Grid row -->
      </div>
    </section>
    <!-- Section: Links  -->

    <!-- Copyright -->
    <div
         class="text-center p-3"
         style="background-color: rgba(0, 0, 0, 0.2)"
         >
      © 2023 Copyright: jole.turbic@gmail.com
        
    </div>
    <!-- Copyright -->
  </footer>
  <!-- Footer -->


  </div>
</template>

<style lang="scss">
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
}

#nav {
  padding: 30px;
  background-color: white !important;

  a {
    font-weight: bold;
    color: #2c3e50;

    &.router-link-exact-active {
      color: #4242b9;
    }
  }
}
</style>
