<template>
  <div id="loading">
    <div class="loader-mask">
      <div class="loader">
        <div></div>
        <div></div>
      </div>
    </div>
  </div>
  <nav>
    <div class="logo">
      <img src="../assets/image/logo.jpg" alt="" />
      <h4>Time Out</h4>
    </div>
    <ul>
      <li><router-link to="/">Home</router-link></li>
      <li>
        <router-link to="/Projects">Projects</router-link>
      </li>
      <li>
        <router-link to="/about">About Us</router-link>
      </li>
      <li>
        <router-link to="/Services">Services</router-link>
      </li>
      <li>
        <router-link to="/about">Contact Us</router-link>
      </li>
    </ul>
    <div class="login">
      <svg-icon type="mdi" :path="path"></svg-icon>
      <div class="Account">
        <p>Hello, Sign in</p>
        <h4>Your Account</h4>
      </div>
    </div>
    <div class="Menu" @click="OpenMenu"><span class="mdi mdi-menu"></span></div>
  </nav>
  <div class="Side" :class="{ active: thisOpen }" @click.self="OpenMenu">
    <ul class="Side_Menu">
      <button class="btn_close" @click="OpenMenu">
        <span class="mdi mdi-close"></span>
      </button>
      <li><router-link to="/">Home</router-link></li>
      <li>
        <router-link to="/Projects">Projects</router-link>
      </li>
      <li>
        <router-link to="/about">About Us</router-link>
      </li>
      <li>
        <router-link to="/about">News</router-link>
      </li>
      <li>
        <router-link to="/about">Contact Us</router-link>
      </li>
      <div class="login">
        <svg-icon type="mdi" :path="path"></svg-icon>

        <div class="Account">
          <p>Hello, Sign in</p>
          <h4>Your Account</h4>
        </div>
      </div>
    </ul>
  </div>
</template>

<script>
import SvgIcon from "@jamescoyle/vue-icon";
import { mdiAccountOutline } from "@mdi/js";
export default {
  components: {
    SvgIcon,
  },
  data() {
    return {
      thisOpen: false,
      path: mdiAccountOutline,
    };
  },
  methods: {
    OpenMenu() {
      this.thisOpen = !this.thisOpen;
    },
  },
};
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
h3 {
  margin: 40px 0 0;
}
ul {
  list-style-type: none;
  padding: 0;
}
li {
  display: inline-block;
  margin: 0 10px;
}
a {
  color: #42b983;
}
</style>
