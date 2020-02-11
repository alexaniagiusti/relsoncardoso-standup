<template>
  <v-footer height="60px" dark padless>
    <v-card class="flex" flat tile>
      <v-card-title class="light-blue accent-4">
        <strong class="subheading">Se conecte em nossas Redes Sociais!</strong>
        <br />

        <v-spacer></v-spacer>

        <v-btn v-for="icon in icons" :key="icon" class="mx-4" dark icon>
          <v-icon size="24px">{{ icon }}</v-icon>
        </v-btn>
      </v-card-title>

      <v-card-text class="py-2 white--text text-center">
        &copy {{ new Date().getFullYear() }} —
        <strong>Relson Cardoso - Todos os Direitos Reservados.</strong>
        <v-spacer></v-spacer>
        <span>
          Desenvolvido Por :
          <a href="#">Alexânia Giusti</a>
        </span>
      </v-card-text>
    </v-card>
  </v-footer>
</template>

<script>
export default {
  data: () => ({
    icons: [
      "mdi-facebook-box",
      "mdi-instagram",
      "mdi-youtube-tv",
      "fab fa-linkedin",
      "fab fa-instagram"
    ]
  })
};
</script>
