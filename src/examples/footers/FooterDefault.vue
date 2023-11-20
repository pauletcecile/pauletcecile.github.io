<script setup>

defineProps({
  brand: {
    type: Object,
    name: String,
    logo: String,
    route: "",
    default: () => ({

      
    })
  },
  socials: {
    type: Array,
    icon: String,
    link: String,
    default: () => [

    ]
  },
  menus: {
    type: Array,
    name: String,
    items: {
      type: Array,
      name: String,
      href: String
    },
    default: () => [



    ]
  }
});
</script>
<template>
  <footer class="footer pt-1 mt-1">
    <div class="container">
      <div class="row">
        <div class="col-12">
          <div class="text-center">
            <p class="text-dark my-4 text-sm font-weight-normal">
              © 2023, made with <i class="fa fa-heart" aria-hidden="true"></i> by Paul & Cécile.
            </p>
          </div>
        </div>
      </div>
    </div>
  </footer>
</template>
