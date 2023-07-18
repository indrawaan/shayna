<template>
  <div class="home">
    <!-- <img alt="Vue logo" src="../assets/logo.png">
    <HelloWorld msg="Welcome to Your Vue.js App"/> -->
    <!-- <header></header> -->
    <HeaderShayna/>
    <OwlCarousel/>
    <WomanShayna/>
    <InstaShayna/>
    <PartnerLogoShayna/>
    <FooterShayna/>
  </div>
</template>

<script>
// @ is an alias to /src
// import HelloWorld from '@/components/HelloWorld.vue'
import HeaderShayna from '@/components/HeaderShayna.vue';
import OwlCarousel from '@/components/OwlCarousel.vue';
import WomanShayna from '@/components/WomanShayna.vue';
import InstaShayna from '@/components/InstaShayna.vue';
import PartnerLogoShayna from '@/components/PartnerLogoShayna.vue';
import FooterShayna from '@/components/FooterShayna.vue';
// import carousel from 'vue-owl-carousel';

export default {
  name: 'HomeView',
  components: {
    HeaderShayna,
    OwlCarousel,
    WomanShayna,
    InstaShayna,
    PartnerLogoShayna,
    FooterShayna,
  }
}
</script>
