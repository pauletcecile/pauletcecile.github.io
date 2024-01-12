<script setup>
// example components
import DefaultNavbar from "../../../examples/navbars/NavbarDefault.vue";
import Header from "../../../examples/Header.vue";

// sections
import Footer from "./Sections/AuthorFooter.vue";
import Profile from "./Sections/AuthorProfile.vue";
import Posts from "./Sections/AuthorPosts.vue";
import Contact from "./Sections/AuthorContact.vue";
import DefaultFooter from "../../../examples/footers/FooterDefault.vue";
import troptrop2 from "@/assets/img/site/troptrop2.jpg";


// image
import image from "@/assets/img/city-profile.jpg";
</script>
<template>
  <DefaultNavbar :sticky="false" transparent />
  <Header>
    <div
      class="page-header min-height-500"
      :style="{ backgroundImage: 
      //`url(https://drive.google.com/uc?export=view&id=1OLN3uYqU-hk8ZSe4RqfnC9UbSOtt93S0)` 
      `url(${troptrop2})`
      }"
      loading="lazy"
    >
      <span class="mask bg-gradient-dark opacity-3"></span>
    </div>
  </Header>
  <div class="card card-body blur shadow-blur mx-3 mx-md-4 mt-n6 mb-4">
    <Profile />
     <!--<Posts />-->
  </div>
  <DefaultFooter />
  <!--<Contact />
  <Footer />>-->
  
</template>
