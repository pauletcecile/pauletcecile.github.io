<script setup>
import ExampleCard from "../Components/ExampleCard.vue";
import MaterialBadge from "../../../components/MaterialBadge.vue";
import pauletcecile from "@/assets/img/site/pauletcecile.png";
import tropplan from "@/assets/img/site/tropplan.jpeg";
import questions from "@/assets/img/site/questions.gif";
import NZ from "@/assets/img/site/NZ.gif";
import marge from "@/assets/img/site/marge.gif";


// images
import imgSigninCover from "@/assets/img/signin-cover.png";

// Set the date we're counting down to
var countDownDate = new Date("Jun 15, 2024 9:00").getTime();

// Update the count down every 1 second
var x = setInterval(function() {

  // Get today's date and time
  var now = new Date().getTime();
    
  // Find the distance between now and the count down date
  var distance = countDownDate - now;
    
  // Time calculations for days, hours, minutes and seconds
  var days = Math.floor(distance / (1000 * 60 * 60 * 24));
  var hours = Math.floor((distance % (1000 * 60 * 60 * 24)) / (1000 * 60 * 60));
  var minutes = Math.floor((distance % (1000 * 60 * 60)) / (1000 * 60));
  var seconds = Math.floor((distance % (1000 * 60)) / 1000);
    
  // Output the result in an element with id="demo"
  document.getElementById("demo").innerHTML = days + "j " + hours + "h "
  + minutes + "min et " + seconds + "sec ";
    
  // If the count down is over, write some text 
  if (distance < 0) {
    clearInterval(x);
    document.getElementById("demo").innerHTML = "EXPIRED";
  }
}, 1000);
</script>
<template>
  <section class="py-5">
    <div class="container">
      <div class="row">
        <div class="row text-center my-sm-5 mt-5">
          <div class="col-lg-6 mx-auto">
            <h2 class="">Nous avons la joie de vous faire part de notre mariage ! 🥳</h2>
            <h1 class="">RDV le 15 juin 2024</h1>
            ...ou aussi dans <b id="demo"></b> ⏳
            <br><br>
           
            <h4 class="">🌴 à Roquebrune-sur-Argens, Var 🌴</h4>
          </div>
        </div>
      </div>
    </div>
    <div class="container mt-5">
      <div class="row">
        <div class="col-md-3  mt-md-0 mt-3">
          <div class="position-sticky" style="top: 100px !important">
            <h2 id="demo"></h2>
            <h3>
              En attendant patiemment... 😎
            </h3>

            <h6 class="text-secondary font-weight-normal">
              ...retrouvez ici toutes les informations essentielles concernant l'événement le plus stylé de l'année !
            </h6>
          </div>
          
        </div>
        
          
            <div class="col-md-4 mt-md-0 mt-5">
              <ExampleCard
                class="shadow-lg"
                title="RSVP - Je confirme ma présence !"
                :image=pauletcecile
                route="contactus"
              />
              <ExampleCard
                classes="shadow-lg"
                title="FAQ"
                :image=questions
                route="author"
              />


            </div>
          
          
            <div class="col-md-4 mt-md-0 mt-5">
              <ExampleCard
                class="shadow-lg"
                title="Infos pratiques"
                :image=tropplan
                route="about"
              />
              <ExampleCard
                class="shadow-lg"
                title="Programme"
                :image=marge
                route="programme"
              />
              <ExampleCard
                classes="mt-5"
                title="Liste de mariage"
                :image=NZ
                route="signin-basic"
              />
            </div>
          
        

      </div>
    </div>
  </section>
</template>
