<script setup>
import { onMounted } from "vue";

//Vue Material Kit 2 components
import MaterialAvatar from "@/components/MaterialAvatar.vue";
import MaterialButton from "@/components/MaterialButton.vue";

// image
import profilePic from "@/assets/img/bruce-mars.jpg";

// material-input
import setMaterialInput from "@/assets/js/material-input";
onMounted(() => {
  setMaterialInput();
});
</script>
<template>
  <section class="py-sm-7 py-5 position-relative">
    <div class="container">
      <div class="row">
        <div class="col-12 mx-auto">
          <div class="mt-n8 mt-md-n9 text-center">
            <div class="blur-shadow-avatar">
              <!--<MaterialAvatar
                size="xxl"
                class="shadow-xl position-relative z-index-2"
                :image="profilePic"
                alt="Avatar"
              />-->
            </div>
          </div>
          <div class="row py-7">
            <div
              class="col-lg-12 col-md-7 z-index-2 position-relative px-md-2 px-sm-5 mx-auto"
            >


     

              <br>

              <h4 class="mb-0">🥞 Où est prévu le brunch le dimanche 16 juin ?</h4>
              <p class="text-lg mb-0">
                Très bonne question ;) !<br>
                Nous vous accueillons le lendemain matin à partir de 12h chez Pierre et Florence Duquesnoy au <a href="https://maps.app.goo.gl/vcDW9yzEZFxokM7v9" target="_blank">89 allée Saint Trophime, 83700 Saint-Raphael</a> pour se remettre ensemble doucement de la veille. <br>
                Il y aura une piscine sur place : prévoyez votre maillot de bain et serviette !
              </p>
              <br>
              <iframe src="https://www.google.com/maps/embed?pb=!1m18!1m12!1m3!1d2896.6923470071133!2d6.7783999999999995!3d43.446141000000004!2m3!1f0!2f0!3f0!3m2!1i1024!2i768!4f13.1!3m3!1m2!1s0x12ce9824d3dbc035%3A0xd19c4f33ff75210c!2s89%20All.%20Saint-Trophime%2C%2083700%20Saint-Rapha%C3%ABl!5e0!3m2!1sen!2sfr!4v1702308294791!5m2!1sen!2sfr" width="100%" height="450" style="border:0;" allowfullscreen="" loading="lazy" referrerpolicy="no-referrer-when-downgrade"></iframe>
              <br>
              <br>
              <p class="text-lg mb-0">
                Comme pour venir la veille depuis la gare TGV, comptez 30 minutes de voiture depuis Tropicana Flore pour vous rendre au lieu du brunch le lendemain chez les parents de Cécile. 
              </p>
              <br>
              <iframe src="https://www.google.com/maps/embed?pb=!1m28!1m12!1m3!1d38966.57205088432!2d6.665468052171796!3d43.45625882724671!2m3!1f0!2f0!3f0!3m2!1i1024!2i768!4f13.1!4m13!3e0!4m5!1s0x12cea5e1b2d8976b%3A0x81218a6fd3ba0c3a!2sTropicana%20Events%2C%20La%20Maurette%2C%20Roquebrune-sur-Argens!3m2!1d43.4466992!2d6.6187451!4m5!1s0x12ce9824d3dbc035%3A0xd19c4f33ff75210c!2s89%20All.%20Saint-Trophime%2C%2083700%20Saint-Rapha%C3%ABl!3m2!1d43.446141!2d6.7783999999999995!5e0!3m2!1sen!2sfr!4v1702312356814!5m2!1sen!2sfr" width="100%" height="450" style="border:0;" allowfullscreen="" loading="lazy" referrerpolicy="no-referrer-when-downgrade"></iframe>
              <br>
              <br>
              <h4 class="mb-0">👶 Peut-on venir avec notre/nos enfant(s) ?</h4>
              <p class="text-lg mb-0">
                Nous avons choisi de privilégier nos amis et notre famille et nous ne serons pas en mesure d'accueillir les enfants dans de bonnes conditions (<b>pas de pièce prévue à cet effet</b> et <b>présence d'un point d'eau non protégé</b>). Merci de faire le maximum pour qu'ils soient gardés à la maison.
              </p>
              <br>

              <h4 class="mb-0"> 🥾 Des idées d'activités a faire dans les environs si on prolonge le weekend ? </h4>
              <p class="text-lg mb-0">
                De une on vous le conseille et de deux, assurement. Il y en a un nombre incalculable! <br>
                🏖️ Pour la team glande, allez farnienter n'importe ou sur le bord de mer, plage - petite crique - base nature de Frejus. Tout est permis. <br>🎨 Pour la team culture, allez visiter Saint-Tropez (si si a cette periode vous pouvez esperer ne pas avoir trop de touristes!), la croisette a Nice ou la beaute de l'arriere pays a Saint Remy de Provence.
                <br>💪 Pour la team sportif, on vous recommande la randonnée des Trois Croix sur le Rocher de Roquebrune que vous pouvez entamer quasiment depuis le site, une session escalade dans les gorges du Blavet ou tout chemin de randonnée dans l'Esterel. 
              </p>
              <br>
              <iframe src="https://fatmap.com/routeid/3555781/depuis-tropicana-flore?fmid=cp" frameborder="" allowfullscreen="" width="100%" height="680"></iframe>
              <br>
              <br>
              <iframe width="100%" height="500" frameborder="0" scrolling="no" marginheight="0" marginwidth="0" sandbox="allow-forms allow-scripts allow-same-origin" src="https://www.geoportail.gouv.fr/embed/visu.html?c=6.60804390170829,43.450399828598336&z=15&l0=GEOGRAPHICALGRIDSYSTEMS.MAPS::GEOPORTAIL:OGC:WMTS(1)&l1=TRACERANDOHIVERNALE::GEOPORTAIL:OGC:WMS(1)&permalink=yes" allowfullscreen></iframe>
            </div>
          </div>
        </div>
      </div>
    </div>
  </section>
</template>
