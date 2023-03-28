<template>
<div class="jumbotron">
 <!--Section: Contact v.2-->
<section class="mb-4">

    <!--Section heading-->
    <h2 class="h1-responsive font-weight-bold text-center my-4">Kontaktieren Sie uns</h2>
    <!--Section description-->
    <p class="text-center w-responsive mx-auto mb-5">Haben Sie eine frage? Bitte zögern Sie nicht und kontaktieren uns. Unser Team meldet sich bald möglichst bei euch.</p>

    <div class="row">

        <!--Grid column-->
        <div class="col-md-9 mb-md-0 mb-5">
            
             <form id="contact-form" name="contact-form" action="https://formbold.com/s/oJpNw" method="POST">

                <!--Grid row-->
                <div class="row">

                    <!--Grid column-->
                    <div class="col-md-6">
                        <div class="md-form mb-0">
                            <input type="text" id="name" name="name" class="form-control">
                            <label for="name" class="">Name</label>
                        </div>
                    </div>
                    <!--Grid column-->

                    <!--Grid column-->
                    <div class="col-md-6">
                        <div class="md-form mb-0">
                            <input type="text" id="email" name="email"  class="form-control">
                            <label for="email" class="">E-mail</label>
                        </div>
                    </div>
                    <!--Grid column-->

                </div>
                <!--Grid row-->

                <!--Grid row-->
                <div class="row">
                    <div class="col-md-12">
                        <div class="md-form mb-0">
                            <input type="text" id="subject" name="subject"  class="form-control">
                            <label for="subject" class="">Betreff</label>
                        </div>
                    </div>
                </div>
                <!--Grid row-->

                <!--Grid row-->
                <div class="row">

                    <!--Grid column-->
                    <div class="col-md-12">

                        <div class="md-form">
                            <textarea type="text" id="message" name="message" rows="2" class="form-control md-textarea"></textarea>
                            <label for="message">Ihre Nachricht</label>
                        </div>

                    </div>
                </div>
                <!--Grid row-->

            </form>

            <div class="text-center text-md-left">
               <a class="btn btn-primary" onclick="document.getElementById('contact-form').submit();">Senden</a>
            </div>
            <div class="status"></div>
        </div>
        <!--Grid column -->

        <!--Grid column-->
        <div class="col-md-3 text-center">
            <ul class="list-unstyled mb-0">
                <li><i class="fas fa-map-marker-alt fa-2x"></i>
                    <p>Blumenrainstrasse 8, 6032 Emmen</p>
                </li>

                <li><i class="fas fa-phone mt-4 fa-2x"></i>
                    <p>+ 41 76 788 62 46</p>
                </li>

                <li><i class="fa-solid fa-envelope mt-4 fa-2x"></i>
                    <p>dalibor.jakovic@gmx.ch</p>
                </li>
            </ul>
        </div>
        <!--Grid column-->

    </div>

</section>
<!--Section: Contact v.2-->
<!--Google map-->
<div id="map-container-google-1" class="z-depth-1-half map-container" style="height: 500px">
  <iframe src="https://maps.google.com/maps?q=Blumenrainstrasse%208&t=&z=13&ie=UTF8&iwloc=&output=embed" frameborder="0"
    style="border:0" allowfullscreen></iframe>
</div>

<!--Google Maps-->

</div>
</template>

<style>
.map-container{
  overflow:hidden;
  padding-bottom:56.25%;
  position:relative;
  height:0;
}
.map-container iframe{
  left:0;
  top:0;
  height:100%;
  width:100%;
  position:absolute;
}
</style>
