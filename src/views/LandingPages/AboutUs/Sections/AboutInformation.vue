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
                description="Notre mariage aura lieu dans la pépiniere Tropicana Flore, au pied du Rocher de Roquebrune. No spoilr mais c'est bien le lieu que vous voyez juste au-dessus."
              />
            </div>



            <div class="">
              <DefaultInfoCard
              
                color="primary"
                icon="public"
                title="Adresse"
                description="1074 La Maurette, 83520 Roquebrune-sur-Argens"
              />
              
              <iframe src="https://www.google.com/maps/embed?pb=!1m14!1m8!1m3!1d3669.864133275631!2d6.618745!3d43.446699!3m2!1i1024!2i768!4f13.1!3m3!1m2!1s0x12cea5e1b2d8976b%3A0x81218a6fd3ba0c3a!2sTropicana%20Events!5e1!3m2!1sen!2sfr!4v1702313181256!5m2!1sen!2sfr" width="100%" height="450" style="border:0;" allowfullscreen="" loading="lazy" referrerpolicy="no-referrer-when-downgrade"></iframe>
            </div>


            <div class="mt-5">
              <DefaultInfoCard
              
                color="primary"
                icon="map"
                title="Comment venir?"
                description=""
              />
              
              <h6>🚅 En train, puis en voiture depuis la gare de St-Raphaël-Valescure</h6>
              <br>
              <iframe src="https://www.google.com/maps/embed?pb=!1m28!1m12!1m3!1d46333.66703281995!2d6.659580647101777!3d43.46364122027078!2m3!1f0!2f0!3f0!3m2!1i1024!2i768!4f13.1!4m13!3e0!4m5!1s0x12ce97efcbd56787%3A0x8d6d969897c170f7!2sGare%20de%20Saint-Rapha%C3%ABl%2FValescure%2C%20Rue%20Waldeck%20Rousseau%2C%20Saint-Rapha%C3%ABl!3m2!1d43.423626999999996!2d6.7690719999999995!4m5!1s0x12cea5e1b2d8976b%3A0x81218a6fd3ba0c3a!2sTropicana%20Events%2C%201074%20La%20Maurette%2C%2083520%20Roquebrune-sur-Argens!3m2!1d43.4466992!2d6.6187451!5e0!3m2!1sen!2sfr!4v1702308703404!5m2!1sen!2sfr" width="100%" height="450" style="border:0;" allowfullscreen="" loading="lazy" referrerpolicy="no-referrer-when-downgrade"></iframe>
              <br>
              <br>
              <h6>✈️ En avion, puis en voiture depuis Nice</h6>
              <br>
              <iframe src="https://www.google.com/maps/embed?pb=!1m28!1m12!1m3!1d185036.22433177952!2d6.751977598140093!3d43.560902940102544!2m3!1f0!2f0!3f0!3m2!1i1024!2i768!4f13.1!4m13!3e0!4m5!1s0x12cdd11897ae99f3%3A0x80532b1cc923c1b4!2sA%C3%A9roport%20Nice%20C%C3%B4te%20d&#39;Azur%20(NCE)%2C%20Rue%20Costes%20et%20Bellonte%2C%20Nice!3m2!1d43.659768899999996!2d7.2148214!4m5!1s0x12cea5e1b2d8976b%3A0x81218a6fd3ba0c3a!2sTropicana%20Events%2C%201074%20La%20Maurette%2C%2083520%20Roquebrune-sur-Argens!3m2!1d43.4466992!2d6.6187451!5e0!3m2!1sen!2sfr!4v1702309306770!5m2!1sen!2sfr" width="100%" height="450" style="border:0;" allowfullscreen="" loading="lazy" referrerpolicy="no-referrer-when-downgrade"></iframe>

              

            </div>
            <div class="row justify-content-start mt-4">
            <DefaultInfoCard
              color="info"
              icon="home"
              title="Où se loger?"
              description="Nous vous conseillons de loger à Saint-Raphael, accès facile depuis la gare TGV. Gros avantage: vous serez à coté de chez Pierre et Florence Duquesnoy pour venir profiter du brunch le lendemain. Il y aura le plus d'airbnb. Il y a des villages vacances.<br>Le lieu se situe a 20-30minutes de Saint-Raphael en voiture."
            />
          </div>

          <div class="mt-5">
              <DefaultInfoCard
                color="primary"
                icon="3d_rotation"
                title="Un peu de contexte..."
                description="Cliquez sur le bouton Play pour une expérience immersive au sein du Rocher de Roquebrune..."
              />
              
              <iframe class="mt-4" src="https://speckle.xyz/embed?stream=bb4ef73a98&autoload=false&hidecontrols=true&hidesidebar=true&hideselectioninfo=true&commentslideshow=true" width="100%" height="450" frameborder="0"></iframe>
            </div>
          </div>

        </div>

      </div>
    </div>
  </section>
</template>
