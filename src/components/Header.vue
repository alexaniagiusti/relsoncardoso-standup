<template>
  <div>
    <v-app-bar v-if="!$vuetify.breakpoint.smAndDown" elevation="0" color="indigo lighten-5" dense>
      <!--<v-toolbar-title
        style="font-family: 'Handlee', cursive; font-size: 19pt; color: #455A64"
      >Relson Cardoso</v-toolbar-title>-->

      <v-spacer></v-spacer>

      <div class="primary_menu">
        <nav class="main_menu">
          <ul>
            <li class="active">
              <a href="#">Início</a>
            </li>
            <li>
              <a href="#">Agenda</a>
            </li>
            <li>
              <a href="#">Biografia</a>
            </li>
            <li>
              <a href="#">Mídias</a>
            </li>
            <li>
              <a href="#">Contratante</a>
            </li>
            <li>
              <a href="#">Contatos</a>
            </li>
            <li>|</li>
            <li>
              <a href="#">
                <span style="font-size: 15pt" class="mdi mdi-facebook-box"></span>
              </a>
            </li>
            <li>
              <a class="page_scroll" href="#">
                <span style="font-size: 15pt" class="mdi mdi-instagram"></span>
              </a>
            </li>
            <li>
              <a class="page_scroll" href="#">
                <span style="font-size: 15pt" class="mdi mdi-whatsapp"></span>
              </a>
            </li>
          </ul>
        </nav>
      </div>
    </v-app-bar>

    <!-- Exibição do Menu mobole -->
    <v-app-bar v-if="$vuetify.breakpoint.smAndDown" absolute flat style="background:rgba(0,0,0,0)">
      <v-app-bar-nav-icon @click.stop="drawer = !drawer"></v-app-bar-nav-icon>
    </v-app-bar>
    <Banner v-if="$vuetify.breakpoint.smAndDown" />
    <v-navigation-drawer v-model="drawer" absolute fixed>
      <v-list nav dense>
        <v-list-item-group v-model="group" active-class="deep-purple--text text--accent-4">
          <v-list-item>
            <v-list-item-title>Início</v-list-item-title>
          </v-list-item>

          <v-list-item>
            <v-list-item-title>Agenda</v-list-item-title>
          </v-list-item>

          <v-list-item>
            <v-list-item-title>Biografia</v-list-item-title>
          </v-list-item>

          <v-list-item>
            <v-list-item-title>Mídias</v-list-item-title>
          </v-list-item>
          <v-list-item>
            <v-list-item-title>Contratante</v-list-item-title>
          </v-list-item>
          <v-list-item>
            <v-list-item-title>Contatos</v-list-item-title>
          </v-list-item>
        </v-list-item-group>
      </v-list>
    </v-navigation-drawer>

    <!-- Final da exibição do menu mobile -->
  </div>
</template>

<style scoped>
.primary_menu .main_menu ul li {
  display: inline-block;
  margin-left: 25px;
  transition: all 0.4s ease-out 0s;
}

.primary_menu .main_menu ul li a {
  font-size: 15px;
  color: #455a64;
  display: block;
  font-family: "Quicksand", sans-serif;
  text-transform: uppercase;
  text-decoration: none;
  font-weight: 600;
  padding: 5px;
}
.primary_menu .main_menu ul li a:hover {
  background-color: #303f9f;
  color: white;
  border-radius: 5px;
}
</style>

<script>
import Banner from "../components/Banner";
export default {
  data: () => ({
    drawer: false,
    group: null
  }),
  components: {
    Banner
  },

  watch: {
    group() {
      this.drawer = false;
    }
  }
};
</script>
