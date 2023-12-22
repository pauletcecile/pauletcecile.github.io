<script setup>
// example components
import DefaultInfoCard from "../../../../examples/cards/infoCards/DefaultInfoCard.vue";
import CenteredBlogCard from "../../../../examples/cards/blogCards/CenteredBlogCard.vue";
</script>

<template>
  
  <section class="">
    
    <div class="container">
      
      <div class="row align-items-center">
 

        <div class=" mt-5">
          <div class="row justify-content-start">
            <div>
              <DefaultInfoCard
                color="primary"
                title="Organisez vite votre venue!"
                description=""
              />
            </div>
            <div :class="`${col ? col : ''}`">
            <p>
              Notre mariage aura lieu dans la pépiniere Tropicana Flore, au pied du Rocher de Roquebrune.<br>
              Vous trouverez dans cette section toutes les informations d'accès à la région, l'adresse du lieu et nos conseils pour les logements.
              <br>
              <br>
            </p>
            </div>

   
            <div class="">
              <DefaultInfoCard
              
                color="primary"
                icon="public"
                title="Adresse"
                description="1074 La Maurette, 83520 Roquebrune-sur-Argens"
              />
              
              <iframe src="https://www.google.com/maps/embed?pb=!1m14!1m8!1m3!1d3669.864133275631!2d6.618745!3d43.446699!3m2!1i1024!2i768!4f13.1!3m3!1m2!1s0x12cea5e1b2d8976b%3A0x81218a6fd3ba0c3a!2sTropicana%20Events!5e1!3m2!1sen!2sfr!4v1702313181256!5m2!1sen!2sfr" width="50%" height="450" style="border:0;" allowfullscreen="" loading="lazy" referrerpolicy="no-referrer-when-downgrade"></iframe>
            </div>
            
      

            <div class="mt-5">
              <DefaultInfoCard
              
                color="primary"
                icon="map"
                title="Comment venir?"
                description=""
              />
              <div class="row">
              <div>
              <h6>🚅 En train, puis en voiture depuis la gare de TGV St-Raphaël-Valescure</h6>
              <br>
              <iframe src="https://www.google.com/maps/embed?pb=!1m28!1m12!1m3!1d46333.66703281995!2d6.659580647101777!3d43.46364122027078!2m3!1f0!2f0!3f0!3m2!1i1024!2i768!4f13.1!4m13!3e0!4m5!1s0x12ce97efcbd56787%3A0x8d6d969897c170f7!2sGare%20de%20Saint-Rapha%C3%ABl%2FValescure%2C%20Rue%20Waldeck%20Rousseau%2C%20Saint-Rapha%C3%ABl!3m2!1d43.423626999999996!2d6.7690719999999995!4m5!1s0x12cea5e1b2d8976b%3A0x81218a6fd3ba0c3a!2sTropicana%20Events%2C%201074%20La%20Maurette%2C%2083520%20Roquebrune-sur-Argens!3m2!1d43.4466992!2d6.6187451!5e0!3m2!1sen!2sfr!4v1702308703404!5m2!1sen!2sfr" width="50%" height="450" style="border:0;" allowfullscreen="" loading="lazy" referrerpolicy="no-referrer-when-downgrade"></iframe>
              <br>
              </div>

              <div>
              <br>
              <h6>✈️ En avion, puis en voiture depuis l'aéroport de Nice Côte d'Azur</h6>
              <br>
              <iframe src="https://www.google.com/maps/embed?pb=!1m28!1m12!1m3!1d185036.22433177952!2d6.751977598140093!3d43.560902940102544!2m3!1f0!2f0!3f0!3m2!1i1024!2i768!4f13.1!4m13!3e0!4m5!1s0x12cdd11897ae99f3%3A0x80532b1cc923c1b4!2sA%C3%A9roport%20Nice%20C%C3%B4te%20d&#39;Azur%20(NCE)%2C%20Rue%20Costes%20et%20Bellonte%2C%20Nice!3m2!1d43.659768899999996!2d7.2148214!4m5!1s0x12cea5e1b2d8976b%3A0x81218a6fd3ba0c3a!2sTropicana%20Events%2C%201074%20La%20Maurette%2C%2083520%20Roquebrune-sur-Argens!3m2!1d43.4466992!2d6.6187451!5e0!3m2!1sen!2sfr!4v1702309306770!5m2!1sen!2sfr" width="50%" height="450" style="border:0;" allowfullscreen="" loading="lazy" referrerpolicy="no-referrer-when-downgrade"></iframe>
              <br>
            
             
            </div>
              </div>
              

            </div>
            
            <div class="row justify-content-start mt-4">
            <DefaultInfoCard
              color="info"
              icon="home"
              title="Où loger?"
              description=""
            />
            </div>
            <div :class="`${col ? col : ''}`">
            
              De manière générale, nous vous conseillons tout logement à Saint-Raphaël et ses environs (Agay, Le Dramont, Fréjus).
              <br>
              <br>
              
              Pour les hôtels, vous trouverez à Saint-Raphaël les classiques avec vue sur mer : L'<b><a href="https://excelsior-hotel.com/fr/" target="_blank">Excelsior</a></b> et le <b><a href="https://www.beausejour-hotel.com/" target="_blank">Beau Séjour</a></b>. Vous pouvez aussi choisir L'<b><a href="https://hotel-frejus-arena.com/fr/" target="_blank">Arena</a></b> dans dans la vieille ville de Fréjus. 
              <br>
              <br>
              Des chaines classiques sont présentes aussi : 
              <ul>
                <li>
                <b><a href="https://www.hotel-lamarina.fr/en/" target="_blank">Best Western La Marina (Port Santa Lucia)</a></b>
                </li>
                <li>
                <b><a href="https://www.hotel-bb.com/fr/hotel/frejus-roquebrune-sur-argens" target="_blank">B&B Hotel Fréjus Roquebrune-sur-Argens</a></b>
                </li>
                <li>
                <b><a href="https://all.accor.com/hotel/2550/index.fr.shtml" target="_blank">Ibis Budget Fréjus Capitou</a></b>
                </li>
                <li>
                <b><a href="https://all.accor.com/hotel/6752/index.fr.shtml" target="_blank">Mercure Thalasso Spa Port Fréjus</a></b>
                </li>
              </ul>
              Enfin, vivez l'expérience Camping - reine dans la région : 
              <ul>
                <li>
                <b><a href="https://www.camping-les-pecheurs.com/fr/" target="_blank">Camping les Pêcheurs </a></b> au bord de l'Argens
                </li>
                <li>
                <b><a href="https://campingdesiscles.com/" target="_blank">Camping du Moulin des Iscles</a></b>
                </li>
                <li>
                <b><a href="https://www.lei-suves.com/fr/" target="_blank">Camping Leï Suves</a></b>
                </li>
                <li>
                <b><a href="https://www.campingdevaudois.com/" target="_blank">Camping de Vaudois</a></b>
                </li>
                <li>
                <b><a href="https://www.camping-le-dattier.com/" target="_blank">Camping Le Dattier</a></b>
                </li>
              </ul>
              Bien que le camping sauvage soit interdit dans l'Esterel, une petite tente plantée à l'abri des regards discrètement ou proche de l'<b><a href="https://www.varmatin.com/religion/le-nouvel-ermite-de-la-grotte-du-rocher-de-roquebrune-sur-argens-aspire-a-la-quietude-735223" target="_blank">ermite en haut du Rocher</a></b> est une option 🧙...
            
          </div>
          

           <!--<div class="mt-5">
              <DefaultInfoCard
                color="primary"
                icon="3d_rotation"
                title="Un peu de contexte..."
                description="Cliquez sur le bouton Play pour une expérience immersive au sein du Rocher de Roquebrune..."
              />
              
              <iframe class="mt-4" src="https://speckle.xyz/embed?stream=bb4ef73a98&autoload=false&hidecontrols=true&hidesidebar=true&hideselectioninfo=true&commentslideshow=true" width="100%" height="450" frameborder="0"></iframe>
            </div>-->
          </div>

        </div>

      </div>
    </div>
  </section>
</template>
