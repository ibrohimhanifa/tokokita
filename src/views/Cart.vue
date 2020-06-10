<template>
  <div class="cart">
    <Header />
    <BreadCrumb />
    <ShoppingCart />
    <Footer />
  </div>
</template>

<script>
// @ is an alias to /src
// import HelloWorld from "@/components/HelloWorld.vue";
import Header from "@/components/Header.vue";
import BreadCrumb from "@/components/BreadCrumb.vue";
import ShoppingCart from "@/components/ShoppingCart.vue";
import Footer from "@/components/Footer.vue";

export default {
  name: "cart",
  components: {
    Header,
    BreadCrumb,
    ShoppingCart,
    Footer
  }
};
</script>
