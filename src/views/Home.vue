<template>
  <div class="home">
    <Header />
    <Carousel />
    <Banner />
    <Gallery />
    <Partner />
    <Footer />
  </div>
</template>

<script>
// @ is an alias to /src
// import HelloWorld from "@/components/HelloWorld.vue";
import Header from "@/components/Header.vue";
import Carousel from "@/components/Carousel.vue";
import Banner from "@/components/Banner.vue";
import Gallery from "@/components/Gallery.vue";
import Partner from "@/components/Partner.vue";
import Footer from "@/components/Footer.vue";

export default {
  name: "home",
  components: {
    Header,
    Carousel,
    Banner,
    Gallery,
    Partner,
    Footer
  }
};
</script>
