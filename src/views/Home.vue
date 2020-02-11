<template>
  <span>
    <Header />
    <Banner v-if="!$vuetify.breakpoint.smAndDown" />
    <Biografia />
    <Midias />
    <Agenda />
    <Footer />
  </span>
</template>

<script>
import Header from "../components/Header.vue";
import Banner from "../components/Banner.vue";
import Biografia from "../components/Biografia";
import Midias from "../components/Midias";
import Agenda from "../components/Agenda";
import Footer from "../components/Footer";

export default {
  components: {
    Header,
    Banner,
    Biografia,
    Midias,
    Agenda,
    Footer
  }
};
</script>

