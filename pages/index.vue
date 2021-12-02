<template>
  <div class="bg-black	h-screen">
    <opening />
    <!-- <navbar />
    <about />
    <buildAbout />
    <div class="container-fluid w-2/2">
      <p class="bg-dark-primary px-24">Lorem ipsum dolor sit amet consectetur adipisicing elit. Amet ut possimus ex enim. Eum distinctio praesentium illo itaque quis veritatis veniam, maxime consequatur deserunt! Et, veritatis! Eligendi fuga nobis et!</p>
    </div> -->
  </div>
</template>

<script>
import opening from "~/components/opening.vue"
import navbar from "~/components/navbar.vue";
import about from "~/components/aboute.vue";
import buildAbout from "~/components/build-about"
export default {
  components: {
    opening,
    navbar,
    about,
    buildAbout
  },
};
</script>
<style scoped>
  @import 'https://pro.fontawesome.com/releases/v5.10.0/css/all.css';

</style>