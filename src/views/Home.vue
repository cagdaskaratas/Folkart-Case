<template>
  <div class="home">
    <Header msg="Welcome to Your Vue.js App"/>
    <Carousel></Carousel>
    <MobileForm></MobileForm>
    <Concept></Concept>
    <Stats></Stats>
    <CreateHome></CreateHome>
    <Promotion></Promotion>
    <MobileLocation></MobileLocation>
    <Map></Map>
    <Footer></Footer>
  </div>
</template>

<script>
// @ is an alias to /src
import Header from '@/components/Header.vue';
import Carousel from '@/components/Carousel.vue';
import Concept from '@/components/Concept.vue';
import Stats from '@/components/Stats.vue';
import Promotion from '@/components/Promotion.vue';
import Map from '@/components/Map.vue';
import Footer from '@/components/Footer.vue';
import MobileForm from '@/components/MobileForm.vue';
import CreateHome from '@/components/CreateHome.vue';
import MobileLocation from '@/components/MobileLocation.vue';

export default {
  name: 'Home',
  components: {
    MobileForm,
    Header,
    Carousel,
    Concept,
    Stats,
    Promotion,
    Map,
    Footer,
    CreateHome,
    MobileLocation,
  },
};
</script>
