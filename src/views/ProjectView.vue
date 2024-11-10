<template>
  <main>
    <div class="container">
      <h1>DAMAC ISLAND</h1>
      <div class="icon_Slider">
        <span class="mdi mdi-twitter"></span>
        <span class="mdi mdi-whatsapp"></span>
        <span class="mdi mdi-facebook"></span>
      </div>
    </div>
  </main>
  <section class="Project_About">
    <div class="container">
      <div class="card">
        <div class="contant">
          <h1>About this project</h1>
          <p>
            The Cube, a three-dimensional symbol of stability and balance, is
            more than just a residential building—it’s a dynamic community in
            Dubai’s MBR District 11. Designed for youth, artists, entrepreneurs,
            and innovators .
          </p>
          <button>REGISTER NOW</button>
        </div>
        <div class="image">
          <img src="../assets/image/Landing_Project.png" alt="" />
        </div>
      </div>
    </div>
    <div class="container">
      <div class="Interiors_Exteriors">
        <div class="Interiors">
          <h1>Interiors</h1>
          <swiper
            slidesPerView="1"
            :spaceBetween="30"
            :loop="true"
            :pagination="true"
            :autoplay="{
              delay: 4000,
              disableOnInteraction: false,
            }"
            :modules="modules"
            class="mySwiper"
          >
            <swiper-slide>
              <img src="../assets/image/Group1.png" alt="" />
            </swiper-slide>
            <swiper-slide>
              <img src="../assets/image/Group2.png" alt="" />
            </swiper-slide>
            <swiper-slide>
              <img src="../assets/image/Group1.png" alt="" />
            </swiper-slide>
            <swiper-slide>
              <img src="../assets/image/Group2.png" alt="" />
            </swiper-slide>
            <swiper-slide>
              <img src="../assets/image/Group1.png" alt="" />
            </swiper-slide>
          </swiper>
        </div>

        <div class="Exteriors">
          <h1>Exteriors</h1>
          <swiper
            slidesPerView="1"
            :spaceBetween="30"
            :loop="true"
            :autoplay="{
              delay: 4000,
              disableOnInteraction: false,
            }"
            :pagination="true"
            :modules="moduless"
            class="mySwiper"
          >
            <swiper-slide>
              <img src="../assets/image/Group2.png" alt="" />
            </swiper-slide>
            <swiper-slide>
              <img src="../assets/image/Group1.png" alt="" />
            </swiper-slide>
            <swiper-slide>
              <img src="../assets/image/Group2.png" alt="" />
            </swiper-slide>
            <swiper-slide>
              <img src="../assets/image/Group1.png" alt="" />
            </swiper-slide>
            <swiper-slide>
              <img src="../assets/image/Group2.png" alt="" />
            </swiper-slide>
          </swiper>
        </div>
      </div>
    </div>
    <div class="container">
      <div class="Key">
        <h1>Key Features</h1>
        <div class="icons">
          <div class="icon">
            <span class="mdi mdi-battery-charging-100"></span>
            <p>CHARGING STATIONS</p>
          </div>
          <div class="icon">
            <span class="mdi mdi-boxing-glove"></span>
            <p>BOXING STUDIO</p>
          </div>
          <div class="icon">
            <span class="mdi mdi-security"></span>
            <p>24/7 SECURITY</p>
          </div>
          <div class="icon">
            <span class="mdi mdi-teddy-bear"></span>
            <p>KIDS CLUB</p>
          </div>
          <div class="icon">
            <span class="mdi mdi-pool"></span>
            <p>ROOFTOP POOL</p>
          </div>
          <div class="icon">
            <span class="mdi mdi-yoga"></span>
            <p>YOGA STUDIO</p>
          </div>
          <div class="icon">
            <span class="mdi mdi-theater"></span>
            <p>ROOFTOP CINEMA</p>
          </div>
          <div class="icon">
            <span class="mdi mdi-dumbbell"></span>
            <p>FITNESS STUDIO</p>
          </div>
        </div>
      </div>
    </div>

    <div class="map">
      <h1>Location map</h1>
      <img src="../assets/image/GroupProject.png" />
    </div>
    <div class="Register">
      <div class="container">
        <h1>Register Now!</h1>
        <div class="card">
          <v-text-field
            v-model="name"
            color="primary"
            label="Full name"
            variant="outlined"
          ></v-text-field>

          <v-text-field
            v-model="email"
            variant="outlined"
            color="primary"
            label="Email"
          ></v-text-field>
          <v-combobox
            label="Country"
            :items="[
              'California',
              'Colorado',
              'Florida',
              'Georgia',
              'Texas',
              'Wyoming',
            ]"
            variant="outlined"
          ></v-combobox>
          <v-textarea label="message" variant="outlined"></v-textarea>

          <button>Complete Registration</button>
        </div>
      </div>
    </div>
  </section>
</template>
<style scoped>
main {
  background-image: url(../assets/image/Landing-Page.png);
}
</style>
<script>
// Import Swiper Vue.js components
import { Swiper, SwiperSlide } from "swiper/vue";

// Import Swiper styles
import "swiper/css";

import "swiper/css/pagination";
// import "swiper/css/navigation";

// import required modules
import { Autoplay, Pagination } from "swiper/modules";

export default {
  components: {
    Swiper,
    SwiperSlide,
  },
  setup() {
    return {
      modules: [Autoplay, Pagination],
      moduless: [Autoplay, Pagination],
    };
  },
  data: () => ({
    name: null,
    email: null,
  }),
};
</script>
