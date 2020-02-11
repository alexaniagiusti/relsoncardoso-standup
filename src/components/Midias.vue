<template>
  <div id="midias">
    <!-- Primeiro Título  -->
    <h1
      style="font-family: 'Asap', sans-serif; text-align:center; color: #fff; padding: 10px;"
    >MÍDIAS</h1>
    <!-- Incio da primeira row -->
    <v-row class="container stretch">
      <v-col cols="4" class="item">
        <v-card hover max-width="344" class="mx-auto">
          <v-list-item>
            <v-list-item-content>
              <v-list-item-title class="headline" style="font-family: 'Anton', sans-serif;">TODOS</v-list-item-title>
            </v-list-item-content>
          </v-list-item>

          <v-img src="https://cdn.vuetifyjs.com/images/cards/mountain.jpg" height="194"></v-img>
        </v-card>
      </v-col>
      <v-col cols="4" class="item">
        <v-card hover max-width="344" class="mx-auto">
          <v-list-item>
            <v-list-item-content>
              <v-list-item-title class="headline" style="font-family: 'Anton', sans-serif;">FOTOS</v-list-item-title>
            </v-list-item-content>
          </v-list-item>

          <v-img src="https://cdn.vuetifyjs.com/images/cards/mountain.jpg" height="194"></v-img>
        </v-card>
      </v-col>
      <v-col cols="4" class="item">
        <v-card hover max-width="344" class="mx-auto">
          <v-list-item>
            <v-list-item-content>
              <v-list-item-title class="headline" style="font-family: 'Anton', sans-serif;">VÍDEOS</v-list-item-title>
            </v-list-item-content>
          </v-list-item>

          <v-img src="https://cdn.vuetifyjs.com/images/cards/mountain.jpg" height="194"></v-img>
        </v-card>
      </v-col>
    </v-row>
  </div>
</template>


<style scoped>
#midias {
  background-image: url(../assets/img/6828.jpg);
}

.container {
  margin: 0 auto;
  display: flex;
}

.stretch {
  align-items: stretch;
}

/* Flex Item */
.item {
  flex: 1;
  margin: 10px;
  padding: 0 10px;
  text-align: center;
  font-size: 12pt;
}
</style>
