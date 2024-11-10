<template>
  <SliderHome />
  <CustomersTrust />
</template>
<script>
import SliderHome from "../components/SliderHome.vue";
import CustomersTrust from "../components/CustomersTrust.vue";
export default {
  name: "HomeView",
  components: {
    CustomersTrust,
    SliderHome,
  },
};
</script>
