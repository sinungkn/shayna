<template>
  <div class="home">
    <HeaderShayna />
    <CarouselShayna />
    <ProductSlider />
    <InstaShayna />
    <ShaynaClients />
    <ShaynaFooter />
  </div>
</template>

<script>
// @ is an alias to /src
// import HelloWorld from "@/components/HelloWorld.vue";
import HeaderShayna from "@/components/HeaderShayna.vue";
import CarouselShayna from "@/components/CarouselShayna.vue";
import ProductSlider from "@/components/ProductSlider.vue";
import InstaShayna from "@/components/InstaShayna.vue";
import ShaynaClients from "@/components/ShaynaClients.vue";
import ShaynaFooter from "@/components/ShaynaFooter.vue";
export default {
  name: "Home",
  components: {
    HeaderShayna,
    CarouselShayna,
    ProductSlider,
    InstaShayna,
    ShaynaClients,
    ShaynaFooter
  }
};
</script>
