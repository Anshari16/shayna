<template>
  <div class="home">
    <HeaderShayna />
    <HeroSection />
    <BanerShayna />
    <InstaShayna />
    <PartnerShayna />
    <FooterShayna />
    
  </div>
</template>

<script>
// // @ is an alias to /src
// import HelloWorld from '@/components/HelloWorld.vue'
import HeaderShayna from '@/components/HeaderShayna.vue';

import HeroSection from '@/components/HeroSection.vue';
import BanerShayna from '@/components/BanerShayna.vue';
import InstaShayna from '@/components/InstaShayna.vue';
import PartnerShayna from '@/components/PartnerShayna.vue';
import FooterShayna from '@/components/FooterShayna.vue';

export default {
  name: 'Home',
  components: {
    // HelloWorld
    HeaderShayna,
    HeroSection,
    BanerShayna,
    InstaShayna,
    PartnerShayna,
    FooterShayna
  }}
</script>
