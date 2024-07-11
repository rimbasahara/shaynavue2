<template>
  <div class="product">
    <HeaderShayna />
    <FooterShayna />
  </div>
</template>

<script>
// @ is an alias to /src test
import HeaderShayna from "@/components/HeaderShayna.vue";
import FooterShayna from "@/components/FooterShayna.vue";

export default {
  name: "ProductView",
  components: {
    HeaderShayna,
    FooterShayna,
  },
};
</script>
