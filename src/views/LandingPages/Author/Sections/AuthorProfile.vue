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


     
              <h4 class="mb-0">Comment venir ?</h4>
              <p class="text-lg mb-0">
                A vous de choisir <br>- Le TGV en vous arretant a la gare TGV Saint-Raphael Valescure. <br>- L'avion avec l'aeroport de Nice qui est le plus proche et ensuite 1h de route.
              </p>
              <br>

              <h4 class="mb-0">Ou loger ?</h4>
              <p class="text-lg mb-0">
                Nous vous conseillons de loger a Saint-Raphael, acces facile depuis la gare TGV. Gros avantage: vous serez a cote pour venir profiter du brunch le lendemain. Il y aura le plus d'airbnb. Il y a des villages vacances.<br>Le lieu se situe a 20-30minutes de Saint-Raphael en voiture.
              </p>
              <br>

              <h4 class="mb-0">Quel est le programme ?</h4>
              <p class="text-lg mb-0">
                Samedi : ca se passe a Roquebrune-sur-Argens a partir de XX heure - jusqu'au bout de la nuit <br>Dimanche: le brunch est a Saint-Raphael
              </p>
              <br>

              <h4 class="mb-0">Ou est prevu le brunch le dimanche 16 juin ?</h4>
              <p class="text-lg mb-0">
                Bienvienue chez Pierre et Florence Duquesnoy ! <br>Rendez-vous a partir de 12h. <br>Nous vous accueillons le lendemain matin au 89 allee Saint Trophime, 83700 Saint-Raphael pour se remettre ensemble doucement de la veille. <br>Piscine sur place, prevoyez votre maillot de bain et serviette.
              </p>
              <br>

              <h4 class="mb-0">Peut-on venir avec notre/nos enfant(s) ?</h4>
              <p class="text-lg mb-0">
                Nous avons choisi de privilégier nos amis et notre famille et nous ne serons pas en mesure d'accueillir les enfants dans de bonnes conditions (<b>pas de pièce prévue à cet effet</b> et <b>présence d'un point d'eau non protégé</b>). Merci de faire le maximum pour qu'ils soient gardés à la maison.
              </p>
              <br>

              <h4 class="mb-0"> Des idees d'activites a faire autours si on prolonge le weekend ? </h4>
              <p class="text-lg mb-0">
                De une on vous le conseille et de deux, assurement. Il y en a un nombre incalculable! <br>- Pour la team glande, allez farnienter n'importe ou sur le bord de mer, plage - petite crique - base nature de Frejus. Tout est permis. <br>- Pour la team sportif, on vous recommande la randonnee des Trois Croix sur le Rocher de Roquebrune, une sessions escalade dans les gorges du Blavet ou tout chemin de randonnee dans l'Esterel. <br>- Pour la team culture, allez visiter Saint-Tropez (si si a cette periode vous pouvez esperer ne pas avoir trop de touristes!), la croisette a Nice ou la beaute de l'arriere pays a Saint Remy de Provence.
              </p>
              <br>

            </div>
          </div>
        </div>
      </div>
    </div>
  </section>
</template>
