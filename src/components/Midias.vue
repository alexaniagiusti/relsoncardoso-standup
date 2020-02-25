<template>
  <div id="midias">
    <!-- Primeiro Título  -->
    <h1
      style="font-family: 'Asap', sans-serif; text-align:center; color: #fff; padding: 10px;"
    >MÍDIAS</h1>
    <v-row class="container stretch">
      <v-col v-for="item in Galeria" :key="item._id" cols="12" md="4" xs="12" class="item">
        <v-card hover max-width="344" class="mx-auto">
          <v-list-item>
            <v-list-item-content>
              <v-list-item-title class="headline" style="font-family: 'Anton', sans-serif;">
                <h5 class="mt-2">{{ item.titulo }}</h5>
              </v-list-item-title>
            </v-list-item-content>
          </v-list-item>

          <v-img :src="item.imagem_capa" height="194"></v-img>
        </v-card>
      </v-col>
    </v-row>
  </div>
</template>

<script>
export default {
  data() {
    return {
      Galeria: []
    };
  },
  methods: {
    getGaleria() {
      this.$http
        .get("/galeria")
        .then(res => {
          this.Galeria = res.data;
        })
        .catch(erro => {
          console.log("caiu no erro");
        });
    }
  },
  created() {
    this.getGaleria();
  }
};
</script>>


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
  text-align: center;
  font-size: 12pt;
}
</style>
