<template>
  <NavBar />
  <router-view />
  <Footer />
</template>

<script>
// @ is an alias to /src
import NavBar from "@/components/NavBar.vue";
import Footer from "@/components/FooterView.vue";
import "./assets/css/style.css";
import "@mdi/font/css/materialdesignicons.css";
import "./assets/css/navbar.css";
import "./assets/css/SliderHome.css";
import "./assets/css/CustomersTrust.css";
import "./assets/css/Project.css";
import "./assets/css/Footer.css";
import "./assets/css/SingleProject.css";
import "./assets/css/Services.css";

export default {
  name: "HomeView",
  components: {
    NavBar,
    Footer,
  },
  data() {
    return {
      loading: true,
      buttonTop: false,
    };
  },
  mounted() {
    setTimeout(() => {
      this.loading = false;
      this.buttonTop = false;
    }, 2000);

    setInterval(() => {
      if (window.scrollY >= "800") {
        this.buttonTop = true;
      }
      if (window.scrollY <= "0") {
        this.buttonTop = false;
      }
    }, 500);
  },
  methods: {
    back_to_top() {
      if (window.scrollY >= "800") {
        window.scrollTo(0, 0);
        this.buttonTop = false;
      }
    },
  },
};
</script>
<style>
#app {
  position: absolute;
  width: 100%;
}
</style>
