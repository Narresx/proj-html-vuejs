<template>
  <div id="app container-fluid">
    <Header :menuItems="menuItems" />
    <Main />
    <Footer />
  </div>
</template>

<script>
import Header from "./components/Header.vue";
import Main from "./components/Main.vue";
import Footer from "./components/Footer.vue";

export default {
  name: "App",
  components: {
    Header,
    Main,
    Footer,
  },
  data() {
    return {
      menuItems: [
        { text: "Home", url: "#" },
        { text: "Rates", url: "#" },
        { text: "Testimonials", url: "#" },
        { text: "FAQ", url: "#" },
        { text: "Blog", url: "#" },
        { text: "Contacts", url: "#" },
        { text: "FREE QUOTE", url: "#" },
      ],
    };
  },
};
</script>

<style lang="scss">
@import "./assets/sass/style.scss";
</style>
