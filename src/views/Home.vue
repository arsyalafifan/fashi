<template>
  <div class="home">
    <HeaderFashi/>
    <HeroSection/>
    <BannerFashi/>
    <InstaFashi/>
    <Logo/>
    <FooterFashi/>
  </div>
</template>

<script>
// @ is an alias to /src
// import HelloWorld from '@/components/HelloWorld.vue'
import HeaderFashi from '@/components/HeaderFashi.vue';
import HeroSection from '@/components/HeroSection.vue';
import BannerFashi from '@/components/BannerFashi.vue';
import InstaFashi from '@/components/InstaFashi.vue';
import Logo from '@/components/Logo.vue';
import FooterFashi from '@/components/FooterFashi.vue';

export default {
  name: 'Home',
  components: {
    HeaderFashi,
    HeroSection,
    BannerFashi,
    InstaFashi,
    Logo,
    FooterFashi
  }
}
</script>
