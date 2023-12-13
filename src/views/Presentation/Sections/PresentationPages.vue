<script setup>
import ExampleCard from "../Components/ExampleCard.vue";
import MaterialBadge from "../../../components/MaterialBadge.vue";

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
                image="https://drive.google.com/uc?export=view&id=1sSVI1LYGWUtIHdSNPfFWu_MyxSvOWD5o"
                route="contactus"
              />
              <ExampleCard
                classes="shadow-lg"
                title="FAQ"
                image="https://media4.giphy.com/media/d1E1YlkOTe4IfdNC/giphy.gif?cid=ecf05e47bsujhjpy8sp7tu1wpxiwmx6o634manwu1ja5opsc&ep=v1_gifs_search&rid=giphy.gif"
                route="author"
              />


            </div>
          
          
            <div class="col-md-4 mt-md-0 mt-5">
              <ExampleCard
                class="shadow-lg"
                title="Infos pratiques"
                image="https://cdn0.mariages.net/vendor/3825/3_2/960/jpeg/97127b0e-a357-4219-a668-9cdb196ac198_3_73825.jpeg"
                route="about"
              />
              <ExampleCard
                class="shadow-lg"
                title="Programme"
                image="https://media1.giphy.com/media/3orif75mohPKmHCPXG/giphy.gif?cid=ecf05e47p5mp43yrn91913lx242tkj5fztuep2xtm94j9evk&ep=v1_gifs_search&rid=giphy.gif&ct=g"
                route="programme"
              />
              <ExampleCard
                classes="mt-5"
                title="Liste de mariage"
                image="https://i.gifer.com/7dNw.gif"
                route="signin-basic"
              />
            </div>
          
        

      </div>
    </div>
  </section>
</template>
