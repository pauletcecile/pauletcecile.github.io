<script setup>
import { onMounted } from "vue";

// example components
import DefaultNavbar from "@/examples/navbars/NavbarDefault.vue";
import Header from "@/examples/Header.vue";

//Vue Material Kit 2 components
import MaterialInput from "@/components/MaterialInput.vue";
import MaterialSwitch from "@/components/MaterialSwitch.vue";
import MaterialButton from "@/components/MaterialButton.vue";
import trop from "@/assets/img/site/troptrop2.jpg";

// material-input
import setMaterialInput from "@/assets/js/material-input";
onMounted(() => {
  setMaterialInput();
});
</script>
<template>
  <DefaultNavbar transparent />
  <Header>
    <div
      class="page-header align-items-start min-vh-100"
      :style="{
        backgroundImage:
          'url(https://drive.google.com/uc?export=view&id=1_KTAMz2S8_1nYY1yXJShgW4lKm3J5upm)'
          //url('../../../assets/img/site/troptrop2.jpg')
          //url('@/assets/img/site/troptrop2.jpg')
      }"
      loading="lazy"
    ><span class="mask bg-gradient-dark opacity-4"></span>
      <span class="mask opacity-0"></span>
      <div class="container my-auto">
        <div class="row">
          <div class="col-lg-5 col-md-8 col-12 mx-auto">
            <div class="card z-index-0 fadeIn3 fadeInBottom">
              <div
                class="card-header p-0 position-relative mt-n4 mx-3 z-index-2"
              >
                <div
                  class="bg-gradient-primary shadow-primary border-radius-lg py-3 pe-1"
                >
                  <h4
                    class="text-white font-weight-bolder text-center mt-2 mb-0"
                  >
                  Programme
                  </h4>

                </div>
              </div>
              <div class="card-body">

                <h5>Samedi 15 juin</h5>
                
                À Tropicana Flore<br>
                • 16h - Arrivée rafraichissante 🍸<br>
                • 16h30 - Cérémonie laïque 💍<br>
                • 17h30 - Cocktail 🥂 + photos de groupe 📷<br>
                • 20h - Dîner 🍽️<br>
                • 22h - Soirée dansante 🕺🏻
                <br>
                <br>
                <h5>Dimanche 16 juin</h5>
                Chez Pierre et Florence Duquesnoy<br>
                • 12h - Brunch
              </div>
            </div>
          </div>
        </div>
      </div>
      <footer class="footer position-absolute bottom-2 py-2 w-100">
        <div class="container">
          <div class="row align-items-center justify-content-lg-between">
            <div class="col-12 col-md-6 my-auto">
              <div
                class="copyright text-center text-sm text-white text-lg-start"
              >
                © {{ new Date().getFullYear() }}, made with
                <i class="fa fa-heart" aria-hidden="true"></i> by Paul & Cécile.
              </div>
            </div>
            <div class="col-12 col-md-6">

            </div>
          </div>
        </div>
      </footer>
    </div>
  </Header>
</template>
