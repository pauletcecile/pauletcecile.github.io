<script setup>
// example components
import DefaultInfoCard from "../../../../examples/cards/infoCards/DefaultInfoCard.vue";
import CenteredBlogCard from "../../../../examples/cards/blogCards/CenteredBlogCard.vue";
</script>
<template>
  
  <section class="py-7">
    
    <div class="container">
      
      <div class="row align-items-center">
 

        <div class="col-lg-12 mt-5">
          <div class="row justify-content-start">
            <div>
              <DefaultInfoCard
                color="primary"
                icon="3d_rotation"
                title="Un peu de contexte..."
                description="Cliquez sur le bouton Play pour une expérience immersive au sein du rocher de roquebrune..."
              />
              
              <iframe class="mt-4" src="https://speckle.xyz/embed?stream=bb4ef73a98&autoload=false&hidecontrols=true&hidesidebar=true&hideselectioninfo=true&commentslideshow=true" width="100%" height="450" frameborder="0"></iframe>
            </div>

            <div class="mt-5">
              <DefaultInfoCard
              
                color="primary"
                icon="public"
                title="Adresse"
                description="1074 La Maurette, 83520 Roquebrune-sur-Argens"
              />
              
              <iframe src="https://www.google.com/maps/embed?pb=!1m18!1m12!1m3!1d1727.6671998965464!2d6.618548925867157!3d43.44701881573728!2m3!1f0!2f0!3f0!3m2!1i1024!2i768!4f13.1!3m3!1m2!1s0x12cea5e1b2d8976b%3A0x81218a6fd3ba0c3a!2sTropicana%20Events!5e0!3m2!1sen!2sfr!4v1700494861126!5m2!1sen!2sfr" width="100%" height="450" style="border:0;" allowfullscreen="allowfullscreen" loading="lazy" referrerpolicy="no-referrer-when-downgrade"></iframe>
            </div>
          </div>
          <!--<div class="row justify-content-start mt-4">
            <DefaultInfoCard
              color="info"
              icon="apps"
              title="Prebuilt components"
              description="We get insulted by others, lose trust for those We get back
                  freezes"
            />
            <DefaultInfoCard
              color="info"
              icon="3p"
              title="Improved platform"
              description="We get insulted by others, lose trust for those We get back
                  freezes"
            />
          </div>-->
        </div>

      </div>
    </div>
  </section>
</template>
