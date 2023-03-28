<template>
 <div class="jumbotron">

<div class="p-5 text-center bg-image rounded-3" style="
    height: 450px;
     background-image: url('https://drive.google.com/uc?export=view&id=1-dNoNHauHSI4zxctQjYHmX61YVee2VWn');
     background-size: cover;
     background-repeat: no-repeat;
     background-position: 50% 100%;
     background-attachment: fixed;
  ">
  <div class="mask" style="background-color: rgba(0, 0, 0, 0.6);">
    <div class="d-flex justify-content-center align-items-center h-100">
      <div class="text-white">
        <h1 class="mb-4"><img src="@/assets/logo3.png" alt="" height="375" class="d-inline-block align-text-top " loading="lazy" /></h1>
      </div>
    </div>
  </div>
</div>

  <div class="container px-4 py-5">
    

    <div class="row row-cols-1 row-cols-md-2 align-items-md-center g-5 py-5">
      <div class="col d-flex flex-column align-items-start gap-2">
        <h3 class="fw-bold">Lernen Sie unsere Dienstleistungen kennen</h3>
        <router-link to="/uberuns"><a class="btn btn-primary btn-lg">Mehr über uns</a> </router-link>
      </div>

      <div class="col">
        <div class="row row-cols-1 row-cols-sm-2 g-4">
          <div class="col d-flex flex-column gap-2">
            <div class="feature-icon-small d-inline-flex align-items-center justify-content-center text-bg-primary bg-gradient fs-4 rounded-3">
              
             <i class="fa-solid fa-map"></i>
              
            </div>
            <h4 class="fw-semibold mb-0">Metallbau</h4>
            <p class="text-muted">Verkauf und Montage von Metalltüren, Fenster, Vordächer und allen anderen Metallkonstruktionen</p>
          </div>

          <div class="col d-flex flex-column gap-2">
            <div class="feature-icon-small d-inline-flex align-items-center justify-content-center text-bg-primary bg-gradient fs-4 rounded-3">
             
              <i class="fa-sharp fa-regular fa-square"></i>

            </div>
            <h4 class="fw-semibold mb-0">Glasbau</h4>
            <p class="text-muted">Verkauf und Montage von neuem Glas und Austausch von bestehendem Glas</p>
          </div>
          <div class="col d-flex flex-column gap-2">
            <div class="feature-icon-small d-inline-flex align-items-center justify-content-center text-bg-primary bg-gradient fs-4 rounded-3">
             
              <i class="fa-solid fa-xmarks-lines"></i>

            </div>
            <h4 class="fw-semibold mb-0">Geländer</h4>
            <p class="text-muted">Produktion und Montage von Glas- Metall- und Chromstahl- Geländer</p>
          </div>


          <div class="col d-flex flex-column gap-2">
            <div class="feature-icon-small d-inline-flex align-items-center justify-content-center text-bg-primary bg-gradient fs-4 rounded-3">
              
              <i class="fa-solid fa-screwdriver-wrench"></i>

            </div>
            <h4 class="fw-semibold mb-0">Montage</h4>
            <p class="text-muted">Montage von Glas- Metall- und Kunststoff- Elementen</p>
          </div>

          <div class="col d-flex flex-column gap-2">
            <div class="feature-icon-small d-inline-flex align-items-center justify-content-center text-bg-primary bg-gradient fs-4 rounded-3">
             
             <i class="fa-solid fa-house-chimney-window"></i>

            </div>
            <h4 class="fw-semibold mb-0">Fenster</h4>
            <p class="text-muted">Montage und Demontage von Fenster aller Art</p>
          </div>
        </div>
      </div>
    </div>
  </div>
  
</div>
</template>

<script>
// @ is an alias to /src
import HelloWorld from '@/components/HelloWorld.vue'

export default {
  name: 'Home',
  components: {
    HelloWorld
  }
}

</script>
<style>
.feature-icon {
  width: 4rem;
  height: 4rem;
  border-radius: .75rem;
}

.icon-link > .bi {
  margin-top: .125rem;
  margin-left: .125rem;
  fill: currentcolor;
  transition: transform .25s ease-in-out;
}
.icon-link:hover > .bi {
  transform: translate(.25rem);
}

.icon-square {
  width: 3rem;
  height: 3rem;
  border-radius: .75rem;
}

.text-shadow-1 { text-shadow: 0 .125rem .25rem rgba(0, 0, 0, .25); }
.text-shadow-2 { text-shadow: 0 .25rem .5rem rgba(0, 0, 0, .25); }
.text-shadow-3 { text-shadow: 0 .5rem 1.5rem rgba(0, 0, 0, .25); }

.card-cover {
  background-repeat: no-repeat;
  background-position: center center;
  background-size: cover;
}

.feature-icon-small {
  width: 3rem;
  height: 3rem;
}

</style>
