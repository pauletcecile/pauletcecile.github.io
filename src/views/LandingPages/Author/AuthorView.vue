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

// image
import image from "@/assets/img/city-profile.jpg";
</script>
<template>
  <DefaultNavbar :sticky="false" />
  <Header>
    <div
      class="page-header min-height-400"
      :style="{ backgroundImage: `url(https://media.tenor.com/p4Qia37e8acAAAAi/faq.gif)` }"
      loading="lazy"
    >
      <span class="mask bg-gradient-dark opacity-8"></span>
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
