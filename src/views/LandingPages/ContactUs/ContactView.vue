<script setup>
import { onMounted } from "vue";

//example components
import DefaultNavbar from "@/examples/navbars/NavbarDefault.vue";
import DefaultFooter from "@/examples/footers/FooterDefault.vue";
import Header from "@/examples/Header.vue";

//image
import image from "@/assets/img/illustrations/illustration-signin.jpg";

//material components
import MaterialInput from "@/components/MaterialInput.vue";
import MaterialTextArea from "@/components/MaterialTextArea.vue";
import MaterialButton from "@/components/MaterialButton.vue";
import pauletcecile from "@/assets/img/site/pauletcecile.png";

// material-input
import setMaterialInput from "@/assets/js/material-input";
onMounted(() => {
  setMaterialInput();
});
</script>
<template style="background-color:#33475b">
          <DefaultNavbar
          transparent 
          :sticky="false"
          
          

        />
        <Header>
    <div
      class="page-header align-items-start min-vh-100"
      :style="{
        backgroundImage:
          //'url(https://drive.google.com/uc?export=view&id=1GWo7dTKxnLG3V8tAYvptwy_gugNOqPkh)'
          `url(${pauletcecile})`
      }"
      loading="lazy"
    >
      <span class="mask opacity-0"></span>
      <div class="container my-auto">
        <div class="row">
          <div class="mt-8 col-xl-4 col-lg-6 col-md-7 d-flex flex-column ms-auto me-auto me-lg-0 ">
            <div class="card z-index-0 fadeIn3 fadeInBottom blur">
              <div
                class="card-header p-0 position-relative mt-n4 mx-3 z-index-2 bg-transparent"
              >
                <div
                  class="bg-gradient-primary shadow-primary border-radius-lg py-3 pe-1"
                >
                  <h4
                    class="text-white font-weight-bolder text-center mt-2 mb-0 "
                  >
                  Confirmez nous votre présence !
                  </h4>

                </div>
              </div>
              <div class="card-body">
                <p class="pb-3">
                  Pour confirmer votre présence à notre mariage, cliquez simplement le bouton ci-dessous et envoyez-nous un mot doux signé <b>avant le 1er mai</b>.
                </p>
                  <form id="contact-form" method="post" autocomplete="off" action="mailto:cecile.duquesnoy@gmail.com; poinetp@gmail.com?subject=Je confirme ma présence !">
                  
<div class="card-body p-0 my-0">
  <!-- {%FOOTER_LINK} 
  <div class="row">
    <div class="col-md-6">
      <MaterialInput
        
        class="input-group-static mb-4"
        type="text"
        label="Prénom"
        placeholder="Antoine"
        
      />
    </div>
    <div class="col-md-6 ps-md-2">
      <MaterialInput
        class="input-group-static mb-4"
        type="text"
        label="Nom"
        placeholder="Dupont"
      />
    </div>
  </div>
  <div class="form-group mb-0 mt-md-0 mt-4">
    <MaterialTextArea
      id="message"
      class="input-group-static mb-4"
      :rows="4"
      placeholder="Grave stylé je viens direct!"
      >Votre message</MaterialTextArea
    >
  </div>-->
  <div class="row">
    <div class="col-md-12 text-center">
      <MaterialButton
        variant="gradient"
        color="primary"
        class="mt-0 mb-0"
        
        >Je confirme ma présence</MaterialButton
      >
    </div>
  </div>
</div>
</form>

<p>
                  <br><br>N'hésitez pas à nous préciser si vous avez des contraintes ou allergies alimentaires, que notre chef puisse les prendre en compte. <br><br>Si vous rencontrez des difficultés, envoyez-nous simplement un email à <b><a href="mailto:cecile.duquesnoy@gmail.com?subject=Je confirme ma présence !">cecile.duquesnoy@gmail.com</a></b> et/ou <b><a href="mailto:poinetp@gmail.com?subject=Je confirme ma présence !">poinetp@gmail.com</a></b>
                </p>
                

              </div>
            </div>
          </div>
        </div>
      </div>
      <footer class="footer position-absolute bottom-2 py-2 w-100">
        <div class="container">
          <div class="row align-items-center justify-content-lg-between">
            <div class="col-12 col-md-6 my-auto">
              <!--<div
                class="copyright text-center text-sm text-white text-lg-start"
              >
                © {{ new Date().getFullYear() }}, made with
                <i class="fa fa-heart" aria-hidden="true"></i> by Paul & Cécile.
              </div>-->
            </div>
            <div class="col-12 col-md-6">

            </div>
          </div>
        </div>
      </footer>
    </div>
  </Header>

  <DefaultFooter />
</template>
