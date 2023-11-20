<script setup>
import { onMounted } from "vue";

//example components
import DefaultNavbar from "@/examples/navbars/NavbarDefault.vue";
import DefaultFooter from "@/examples/footers/FooterDefault.vue";

//image
import image from "@/assets/img/illustrations/illustration-signin.jpg";

//material components
import MaterialInput from "@/components/MaterialInput.vue";
import MaterialTextArea from "@/components/MaterialTextArea.vue";
import MaterialButton from "@/components/MaterialButton.vue";

// material-input
import setMaterialInput from "@/assets/js/material-input";
onMounted(() => {
  setMaterialInput();
});
</script>
<template>
  <div class="container position-sticky z-index-sticky top-0">
    <div class="row">
      <div class="col-12">
        <DefaultNavbar 
          :sticky="true"

        />
      </div>
    </div>
  </div>
  <section>
    <div class="page-header min-vh-100">
      <div class="container">
        <div class="row">
          <div
            class="col-6 d-lg-flex d-none h-100 my-auto pe-0 position-absolute top-0 start-0 text-center justify-content-center flex-column"
          >
            <div
              class="position-relative h-100 m-3 px-7 border-radius-lg d-flex flex-column justify-content-center"
              :style="{
                backgroundImage: `url(https://drive.google.com/uc?export=view&id=1ywoz6nLk29rgkjGfFtpFqBIrPfhljOho)`,
                backgroundSize: 'cover',
              }"
              loading="lazy"
            ></div>
          </div>
          <div
            class="mt-8 col-xl-5 col-lg-6 col-md-7 d-flex flex-column ms-auto me-auto ms-lg-auto me-lg-5"
          >
            <div
              class="card d-flex blur justify-content-center shadow-lg my-sm-0 my-sm-6 mt-8 mb-5"
            >
              <div
                class="card-header p-0 position-relative mt-n4 mx-3 z-index-2 bg-transparent"
              >
                <div
                  class="bg-gradient-primary shadow-primary border-radius-lg p-3"
                >
                  <h3 class="text-white text-success mb-0">Confirmez nous votre présence !</h3>
                </div>
              </div>
              <div class="card-body">
                <p class="pb-3">
                  Pour confirmer votre présence à notre mariage, cliquez simplement le bouton ci-dessous. Si vous rencontrez des difficultés, envoyez-nous simplement un email à <b><a href="mailto:cecile.duquesnoy@gmail.com?subject=Je confirme ma présence !">cecile.duquesnoy@gmail.com</a></b> et/ou <b><a href="mailto:poinetp@gmail.com?subject=Je confirme ma présence !">poinetp@gmail.com</a></b>
                </p>
                
                <form id="contact-form" method="post" autocomplete="off" action="mailto:cecile.duquesnoy@gmail.com; poinetp@gmail.com?subject=Je confirme ma présence !">

                  <div class="card-body p-0 my-3">
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
                          class="mt-3 mb-0"
                          
                          >Je confirme ma présence</MaterialButton
                        >
                      </div>
                    </div>
                  </div>
                </form>
              </div>
            </div>
          </div>
        </div>
      </div>
    </div>
  </section>
  <DefaultFooter />
</template>
