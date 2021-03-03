<template>
  <div class="home">
   <HeaderAldian />
   <HeroAldian />
   <BennerAldian />
   <InstaAldian />
   <PatnerAldian />
   <FooterAldian />
  </div>
</template>

<script>
// @ is an alias to /src
// import HelloWorld from '@/components/HelloWorld.vue'
import HeaderAldian from "@/components/HeaderAldian.vue";
import HeroAldian from "@/components/HeroAldian.vue";
import BennerAldian from "@/components/BennerAldian.vue";
import InstaAldian from "@/components/InstaAldian.vue";
import PatnerAldian from "@/components/PatnerAldian.vue";
import FooterAldian from "@/components/FooterAldian.vue";


export default {
  name: 'Home',
  components: {
    HeaderAldian,
    HeroAldian,
    BennerAldian,
    InstaAldian,
    PatnerAldian,
    FooterAldian
  }
};
</script>
