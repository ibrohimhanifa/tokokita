<template>
  <div class="product">
    <Header />
    <BreadCrumb />
    <DetailProduct />
    <RelatedProduct />
    <Footer />
  </div>
</template>

<script>
// @ is an alias to /src
// import HelloWorld from "@/components/HelloWorld.vue";
import Header from "@/components/Header.vue";
import BreadCrumb from "@/components/BreadCrumb.vue";
import DetailProduct from "@/components/DetailProduct.vue";
import RelatedProduct from "@/components/RelatedProduct.vue";
import Footer from "@/components/Footer.vue";

export default {
  name: "product",
  components: {
    Header,
    BreadCrumb,
    DetailProduct,
    RelatedProduct,
    Footer
  }
};
</script>
