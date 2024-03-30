<template>
<section class="section services-section" id="services">
    <div class="container">
        <div class="row">
            <div class="col-lg-6">
                <div class="section-title">
                    <h2>Wer sind wir?</h2>
                    <p>Wir sind ein Unternehmen mit langjähriger Erfahrung im Verkauf und der Montage aller Arten von Geländer, Glas, Türen und Fenster</p>
                </div>
            </div>
        </div>
        <div class="row">
            <!-- feaure box -->
            <div class="col-sm-6 col-lg-4">
             <router-link to="/metallbau" style="text-decoration: none"> 
               
                <div class="feature-box-1" style="background-image: url('https://drive.google.com/thumbnail?sz=w5000&id=1FnhUX1zUJXtIxqRVy_N3Bo5FoutleghT'); background-size: cover;
     background-repeat: no-repeat;
     background-position: 50% 100%;
     height: 170px">
                    <div class="mask" style="background-color: rgba(0, 0, 0, 0.6); height:120px;">
                     <div class="d-flex justify-content-center align-items-center h-100">
      <h5>Metallbau</h5>
                    </div>
                </div>
                </div>
              
                </router-link>
            </div>
            <!-- / -->
            
            <!-- feaure box -->
            <div class="col-sm-6 col-lg-4">
                <router-link to="/montagen" style="text-decoration: none">
                <div class="feature-box-1" style="background-image: url('https://drive.google.com/thumbnail?sz=w5000&id=1XCjLTocycuDUhzs0wBqa_zKuSXZElwaS'); background-size: cover;
     background-repeat: no-repeat;
     background-position: 50% 100%;
     height: 170px">
                    <div class="mask" style="background-color: rgba(0, 0, 0, 0.6); height:120px;">
                     <div class="d-flex justify-content-center align-items-center h-100">
      <h5>Montage</h5>
                    </div>
                </div>
                </div>
                </router-link>
            </div>
            <!-- / -->
            <!-- feaure box -->
            <div class="col-sm-6 col-lg-4">
                <router-link to="/fenster" style="text-decoration: none">
                  
                <div class="feature-box-1" style="background-image: url('https://drive.google.com/thumbnail?sz=w5000&id=1EGAgA4dxPcavCbh42f35nAc6UY04S4nm'); background-size: cover;
     background-repeat: no-repeat;
     background-position: 50% 100%;
     height: 170px">
                    <div class="mask" style="background-color: rgba(0, 0, 0, 0.6); height:120px;">
                    <div class="d-flex justify-content-center align-items-center h-100">
      <h5>Fenster</h5>
    </div>
                </div>
                </div>
                </router-link>
            </div>
            <!-- / -->
            <!-- feaure box -->
            <div class="col-sm-6 col-lg-4">
                <router-link to="/glasbau" style="text-decoration: none">
                <div class="feature-box-1" style="background-image: url('https://drive.google.com/thumbnail?sz=w5000&id=17u6f7T8mzOrPcPe8QJF63K7olhidl5YS'); background-size: cover;
     background-repeat: no-repeat;
     background-position: 50% 100%;
     height: 170px">
                   <div class="mask" style="background-color: rgba(0, 0, 0, 0.6); height:120px;">
                     <div class="d-flex justify-content-center align-items-center h-100">
      <h5>Glasbau</h5>
                     </div>
                </div>
                </div>
                </router-link>
            </div>
            <!-- / -->
            <!-- feaure box -->
            <div class="col-sm-6 col-lg-4">
                <router-link to="/gelander" style="text-decoration: none">
                <div class="feature-box-1" style="background-image: url('https://drive.google.com/thumbnail?sz=w5000&id=1-dNoNHauHSI4zxctQjYHmX61YVee2VWn'); background-size: cover;
     background-repeat: no-repeat;
     background-position: 50% 100%;
     height: 170px">
                <div class="mask" style="background-color: rgba(0, 0, 0, 0.6); height:120px;">
                     <div class="d-flex justify-content-center align-items-center h-100">
      <h5>Geländer</h5>
                     </div>
                </div>
                </div>
                </router-link>
            </div>
            <!-- / -->
        </div>
    </div>
</section>                    
</template>

<style>

body{margin-top:20px;}

/* Feature Box
---------------------*/
.feature-box-1 {
  padding: 32px;
  box-shadow: 0 0 30px rgba(31, 45, 61, 0.125);
  margin: 15px 0;
  position: relative;
  z-index: 1;
  border-radius: 10px;
  overflow: hidden;
  -moz-transition: ease all 0.35s;
  -o-transition: ease all 0.35s;
  -webkit-transition: ease all 0.35s;
  transition: ease all 0.35s;
  top: 0;
}
.feature-box-1 * {
  -moz-transition: ease all 0.35s;
  -o-transition: ease all 0.35s;
  -webkit-transition: ease all 0.35s;
  transition: ease all 0.35s;
}
.feature-box-1 .icon {
  width: 70px;
  height: 70px;
  line-height: 70px;
  background: #375ae7;
  color: #ffffff;
  text-align: center;
  border-radius: 50%;
  margin-bottom: 22px;
  font-size: 27px;
}
.feature-box-1 .icon i {
  line-height: 70px;
}
.feature-box-1 h5 {
  color: white;
  font-weight: 600;
}
.feature-box-1 p {
  margin: 0;
  color:white;
}
.feature-box-1:after {
  content: "";
  position: absolute;
  top: 0;
  bottom: 0;
  left: auto;
  right: 0;
  border-radius: 10px;
  width: 0;
  background: #20247b;
  z-index: -1;
  -moz-transition: ease all 0.35s;
  -o-transition: ease all 0.35s;
  -webkit-transition: ease all 0.35s;
  transition: ease all 0.35s;
}
.feature-box-1:hover {
  top: -5px;
}
.feature-box-1:hover h5 {
  color: #ffffff;
}
.feature-box-1:hover p {
  color: rgba(255, 255, 255, 0.8);
}
.feature-box-1:hover:after {
  width: 100%;
  height: 100%;
  border-radius: 10px;
  left: 0;
  right: auto;
}
.section {
    padding: 100px 0;
    position: relative;
}
.section-title {
    padding-bottom: 45px;
}
.section-title h2 {
    font-weight: 700;
    color: #20247b;
    font-size: 45px;
    margin: 0 0 15px;
    border-left: 5px solid #fc5356;
    padding-left: 15px;
}
</style>
