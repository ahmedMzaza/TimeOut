<template>
  <section class="Swiper_contant">
    <div class="container">
      <h1>10.000 Customers trust us!</h1>
      <swiper
        :breakpoints="{
          '140': {
            slidesPerView: 2,
            spaceBetween: 20,
          },
          '640': {
            slidesPerView: 4,
            spaceBetween: 20,
          },
          '768': {
            slidesPerView: 5,
            spaceBetween: 40,
          },
          '1024': {
            slidesPerView: 6,
            spaceBetween: 50,
          },
        }"
        :spaceBetween="30"
        :loop="true"
        :autoplay="{
          delay: 4000,
          disableOnInteraction: false,
        }"
        :modules="modules"
        class="mySwiper"
      >
        <swiper-slide>
          <img src="../assets/image/barnd-1.png" alt="" />
        </swiper-slide>
        <swiper-slide>
          <img src="../assets/image/barnd-2.png" alt="" />
        </swiper-slide>
        <swiper-slide>
          <img src="../assets/image/barnd-3.png" alt="" />
        </swiper-slide>
        <swiper-slide>
          <img src="../assets/image/barnd-4.png" alt="" />
        </swiper-slide>
        <swiper-slide>
          <img src="../assets/image/barnd-5.png" alt="" />
        </swiper-slide>
        <swiper-slide>
          <img src="../assets/image/barnd-6.png" alt="" />
        </swiper-slide>
        <swiper-slide>
          <img src="../assets/image/barnd-1.png" alt="" />
        </swiper-slide>
        <swiper-slide>
          <img src="../assets/image/barnd-2.png" alt="" />
        </swiper-slide>
        <swiper-slide>
          <img src="../assets/image/barnd-3.png" alt="" />
        </swiper-slide>
      </swiper>
    </div>
  </section>
  <section class="tp-about">
    <div class="container">
      <div class="image">
        <img src="../assets/image/about-thumb-1.jpg" alt="" />
      </div>
      <div class="tp-Contant">
        <div class="tp-about-heading">
          <h3 class="tp-section-title">Engage in lively urban lifestyle</h3>
        </div>
        <p>
          At the heart of each of our investments is a strategy to build or buy
          a <br />
          portfolio of real estate
          <span>12+ years of experience</span> a specific user <br />
          group. We believe that by doing this well we create better
          <br />
          outcomes, not only for our investors, but for society as a
          <br />
          whole. Matter invests in companies.
        </p>
        <div class="tp-about-btn">
          <a class="tp-btn" href="about.html">
            <span class="btn-wrap">
              <b class="text-1">About Company</b>
            </span>
          </a>
          <a class="tp-btn btn-2" href="property-style-1.html">
            <span class="btn-wrap">
              <b class="text-1">View Property</b>
            </span>
          </a>
        </div>
      </div>
    </div>
  </section>
  <section class="Subtcribe">
    <div class="container">
      <div class="text_Subtcribe">
        <h1>Subscribe to our newsletter</h1>
        <p>
          Our articles, guides, and videos help you through the process, start
          to finish.
        </p>
        <button>Get started</button>
      </div>
    </div>
  </section>
  <section class="Developers">
    <div class="container">
      <h1>Our Developers</h1>
      <div class="Develop">
        <div class="card">
          <div class="image">
            <img src="../assets/image/image-1.png" />
          </div>
          <div class="contant">
            <h4>LUXURY ONE REAL ES...</h4>
            <p>Location : Dubai</p>
            <p>Agent : 1</p>
            <div class="Datas">
              <h5>For sale : 80</h5>
              <h5>For rent : 25</h5>
            </div>
          </div>
        </div>
        <div class="card">
          <div class="image">
            <img src="../assets/image/image-2.png" />
          </div>
          <div class="contant">
            <h4>LUXURY ONE REAL ES...</h4>
            <p>Location : Dubai</p>
            <p>Agent : 1</p>
            <div class="Datas">
              <h5>For sale : 80</h5>
              <h5>For rent : 25</h5>
            </div>
          </div>
        </div>
        <div class="card">
          <div class="image">
            <img src="../assets/image/image-3.png" />
          </div>
          <div class="contant">
            <h4>LUXURY ONE REAL ES...</h4>
            <p>Location : Dubai</p>
            <p>Agent : 1</p>
            <div class="Datas">
              <h5>For sale : 80</h5>
              <h5>For rent : 25</h5>
            </div>
          </div>
        </div>
        <div class="card">
          <div class="image">
            <img src="../assets/image/image-4.png" />
          </div>
          <div class="contant">
            <h4>LUXURY ONE REAL ES...</h4>
            <p>Location : Dubai</p>
            <p>Agent : 1</p>
            <div class="Datas">
              <h5>For sale : 80</h5>
              <h5>For rent : 25</h5>
            </div>
          </div>
        </div>
      </div>
      <div>
        <button>Browse All</button>
      </div>
    </div>
  </section>
  <section class="TimeOut">
    <div class="container">
      <div class="contant">
        <h1>Join Time Out and experience today</h1>
        <button>Discover projects</button>
      </div>
    </div>
  </section>
  <section class="OurProject">
    <div class="container">
      <h1>Explore the neighbourhoods to our projects</h1>
      <div class="Project">
        <div class="row">
          <div class="col-8">
            <img src="../assets/image/Rectangle-1.png" alt="" />
          </div>
          <div class="col-4">
            <img src="../assets/image/Rectangle-2.png" alt="" />
          </div>
        </div>
        <div class="row">
          <div class="col-4">
            <img src="../assets/image/Rectangle-3.png" alt="" />
          </div>
          <div class="col-8">
            <img src="../assets/image/Rectangle-4.png" alt="" />
          </div>
        </div>
      </div>
    </div>
  </section>
  <section class="Commints">
    <div class="container">
      <h1>What People say about our Developers</h1>

      <swiper
        :spaceBetween="30"
        :centeredSlides="true"
        :slidesPerView="3"
        :loop="true"
        :autoplay="{
          delay: 4000,
          disableOnInteraction: false,
        }"
        :pagination="{
          clickable: true,
        }"
        :navigation="true"
        :modules="module"
        class="mySwiper"
      >
        <swiper-slide>
          <div class="card">
            <div class="rate">
              <span class="mdi mdi-star"></span>
              <span class="mdi mdi-star"></span>
              <span class="mdi mdi-star"></span>
              <span class="mdi mdi-star"></span>
              <span class="mdi mdi-star"></span>
            </div>
            <h4>
              “ Is it possible to love your credit card processor? with Time Out
              is easy ! “
            </h4>
            <div class="account">
              <img src="../assets/image/Frame-1.png" alt="" />
              <div class="data">
                <p class="name">Lana Ray</p>
                <p class="email">Founder , CEO</p>
              </div>
            </div>
          </div>
        </swiper-slide>
        <swiper-slide>
          <div class="card">
            <div class="rate">
              <span class="mdi mdi-star"></span>
              <span class="mdi mdi-star"></span>
              <span class="mdi mdi-star"></span>
              <span class="mdi mdi-star"></span>
              <span class="mdi mdi-star"></span>
            </div>
            <h4>
              “ Is it possible to love your credit card processor? with Time Out
              is easy ! “
            </h4>
            <div class="account">
              <img src="../assets/image/Frame-1.png" alt="" />
              <div class="data">
                <p class="name">Lana Ray</p>
                <p class="email">Founder , CEO</p>
              </div>
            </div>
          </div>
        </swiper-slide>
        <swiper-slide>
          <div class="card">
            <div class="rate">
              <span class="mdi mdi-star"></span>
              <span class="mdi mdi-star"></span>
              <span class="mdi mdi-star"></span>
              <span class="mdi mdi-star"></span>
              <span class="mdi mdi-star"></span>
            </div>
            <h4>
              “ Is it possible to love your credit card processor? with Time Out
              is easy ! “
            </h4>
            <div class="account">
              <img src="../assets/image/Frame-1.png" alt="" />
              <div class="data">
                <p class="name">Lana Ray</p>
                <p class="email">Founder , CEO</p>
              </div>
            </div>
          </div>
        </swiper-slide>
        <swiper-slide>
          <div class="card">
            <div class="rate">
              <span class="mdi mdi-star"></span>
              <span class="mdi mdi-star"></span>
              <span class="mdi mdi-star"></span>
              <span class="mdi mdi-star"></span>
              <span class="mdi mdi-star"></span>
            </div>
            <h4>
              “ Is it possible to love your credit card processor? with Time Out
              is easy ! “
            </h4>
            <div class="account">
              <img src="../assets/image/Frame-1.png" alt="" />
              <div class="data">
                <p class="name">Lana Ray</p>
                <p class="email">Founder , CEO</p>
              </div>
            </div>
          </div>
        </swiper-slide>
        <swiper-slide>
          <div class="card">
            <div class="rate">
              <span class="mdi mdi-star"></span>
              <span class="mdi mdi-star"></span>
              <span class="mdi mdi-star"></span>
              <span class="mdi mdi-star"></span>
              <span class="mdi mdi-star"></span>
            </div>
            <h4>
              “ Is it possible to love your credit card processor? with Time Out
              is easy ! “
            </h4>
            <div class="account">
              <img src="../assets/image/Frame-1.png" alt="" />
              <div class="data">
                <p class="name">Lana Ray</p>
                <p class="email">Founder , CEO</p>
              </div>
            </div>
          </div>
        </swiper-slide>
        <swiper-slide>
          <div class="card">
            <div class="rate">
              <span class="mdi mdi-star"></span>
              <span class="mdi mdi-star"></span>
              <span class="mdi mdi-star"></span>
              <span class="mdi mdi-star"></span>
              <span class="mdi mdi-star"></span>
            </div>
            <h4>
              “ Is it possible to love your credit card processor? with Time Out
              is easy ! “
            </h4>
            <div class="account">
              <img src="../assets/image/Frame-1.png" alt="" />
              <div class="data">
                <p class="name">Lana Ray</p>
                <p class="email">Founder , CEO</p>
              </div>
            </div>
          </div>
        </swiper-slide>
      </swiper>
    </div>
  </section>
</template>

<script>
// Import Swiper Vue.js components
import { Swiper, SwiperSlide } from "swiper/vue";

// Import Swiper styles
import "swiper/css";

import "swiper/css/pagination";
import "swiper/css/navigation";

// import required modules
import { Autoplay, Pagination, Navigation } from "swiper/modules";

export default {
  components: {
    Swiper,
    SwiperSlide,
  },
  setup() {
    return {
      modules: [Autoplay],
      module: [Autoplay, Pagination, Navigation],
    };
  },
};
</script>
