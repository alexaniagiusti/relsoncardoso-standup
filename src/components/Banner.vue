<template>
  <div>
    <v-carousel v-if="!$vuetify.breakpoint.smAndDown" height="670px" app show-arrows-on-hover>
      <v-carousel-item
        v-for="(item,i) in items"
        :key="i"
        :src="item.src"
        reverse-transition="fade-transition"
        transition="fade-transition"
      ></v-carousel-item>
    </v-carousel>
    <v-img v-else src="/assets/img/capa-mobile.png"></v-img>
  </div>
</template>

<script>
export default {
  data() {
    return {
      items: [
        {
          src:
            "https://firebasestorage.googleapis.com/v0/b/relson-cardoso.appspot.com/o/_SMP7473.jpg?alt=media&token=633035e3-e1ba-4f7f-8c94-f4e223b7cea7"
        },
        {
          src:
            "https://firebasestorage.googleapis.com/v0/b/relson-cardoso.appspot.com/o/_SMP7389.jpg?alt=media&token=a3a0e688-eed9-4517-b2d2-4c6357046c6d"
        },
        {
          src:
            "https://firebasestorage.googleapis.com/v0/b/relson-cardoso.appspot.com/o/_SMP7395.jpg?alt=media&token=6ce9de95-67c8-4aec-ab57-fd897d6571e5"
        },
        {
          src:
            "https://firebasestorage.googleapis.com/v0/b/relson-cardoso.appspot.com/o/_SMP7479.jpg?alt=media&token=9f5f31e5-8bf7-4e27-98cd-7b6f0a877eec"
        }
      ]
    };
  }
};
</script>
