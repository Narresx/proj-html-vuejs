<template>
  <div id="app" class="overflow-hidden">
    <Header :menuItems="menuItems" />
    <Main />
    <Footer :footerItems="footerItems" :footerItems1="footerItems1" />
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
      ],
      footerItems: [
        { text: "> Home", url: "#" },
        { text: "> Rates", url: "#" },
        { text: "> Testimonials", url: "#" },
        { text: "> Blog", url: "#" },
        { text: "> Free Quote", url: "#" },
      ],
      footerItems1: [
        { text: "> Heading Out To Collage?", url: "#" },
        { text: "> Moving Your Business?", url: "#" },
        { text: "> Outstanding Quality", url: "#" },
        { text: "> Cost of Moving", url: "#" },
        { text: "> Best Moving Tips", url: "#" },
      ],
    };
  },
};
</script>

<style lang="scss">
@import "./assets/sass/style.scss";
</style>
