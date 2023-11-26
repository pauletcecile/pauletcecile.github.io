<script setup>
import { onMounted } from "vue";

// example components
import DefaultNavbar from "@/examples/navbars/NavbarDefault.vue";
import Header from "@/examples/Header.vue";

//Vue Material Kit 2 components
import MaterialInput from "@/components/MaterialInput.vue";
import MaterialSwitch from "@/components/MaterialSwitch.vue";
import MaterialButton from "@/components/MaterialButton.vue";

// material-input
import setMaterialInput from "@/assets/js/material-input";
onMounted(() => {
  setMaterialInput();
});
</script>
<template>
  <DefaultNavbar  />
  <Header>
    <div
      class="page-header align-items-start min-vh-100"
      :style="{
        backgroundImage:
          'url(https://i.gifer.com/7dNw.gif)'
      }"
      loading="lazy"
    >
      <span class="mask opacity-0"></span>
      <div class="container my-auto">
        <div class="row">
          <div class="col-lg-4 col-md-8 col-12 mx-auto">
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
                  ✈️🌏🏔️🏝️
                  </h4>

                </div>
              </div>
              <div class="card-body">
                Cette liste de mariage ne comporte finalement qu'un seul article...<br>
                <br>
                En effet, notre envie insatiable de voyage et d'aventure nous a mené à rêver d'un voyage en Nouvelle-Zélande. Vous pouvez nous aider à le réaliser :<br>
                <br>
                • soit par virement - un RIB vous sera communiqué par e-mail une fois que vous aurez confirmé votre présence.<br>
                • soit en nous déposant une enveloppe dans l'urne le jour J !
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
