<template>
  <span>
    <Header />
    <Banner v-if="!$vuetify.breakpoint.smAndDown" />
    <Biografia />
    <Midias />
  </span>
</template>

<script>
import Header from "../components/Header.vue";
import Banner from "../components/Banner.vue";
import Biografia from "../components/Biografia";
import Midias from "../components/Midias";

export default {
  components: {
    Header,
    Banner,
    Biografia,
    Midias
  }
};
</script>

