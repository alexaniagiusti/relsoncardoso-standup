<template>
  <div>
    <v-app-bar
      color="indigo lighten-5"
      dense
    >
      <v-toolbar-title>Relson Cardoso</v-toolbar-title>

      <v-spacer></v-spacer>

      <div class="primary_menu">
        <nav class="main_menu">
          <ul>
            <li class="active"><a class="page_scroll" href="#">Início</a></li>
            <li><a class="page_scroll" href="#">Agenda</a></li>
            <li><a class="page_scroll" href="#">Bibliografia</a></li>
            <li><a class="page_scroll" href="#">Mídias</a></li>
            <li><a class="page_scroll" href="#">Contratante</a></li>
            <li><a class="page_scroll" href="#">Contatos</a></li>
            <li><a class="page_scroll" href="#"> | </a></li>
            <li><a class="page_scroll" href="#"> Facebook </a></li>
            <li><a class="page_scroll" href="#"> Instagram </a></li>
            <li><a class="page_scroll" href="#"> WhatsApp </a></li>
          </ul>
        </nav>
      </div>
    </v-app-bar>
  </div>
</template>

<style scoped>
.primary_menu .main_menu ul li {
        display: inline-block;
        margin-left: 40px;
        -webkit-transition: all 0.4s ease-out 0s;
        -moz-transition: all 0.4s ease-out 0s;
        -ms-transition: all 0.4s ease-out 0s;
        -o-transition: all 0.4s ease-out 0s;
        transition: all 0.4s ease-out 0s; }

.primary_menu .main_menu ul li a {
          font-size: 15px;
          color: #000;
          display: block;
          padding: 42px 0;
          font-family: "Quicksand", sans-serif;
          text-transform: uppercase;
          font-weight: 600;
          -webkit-transition: all 0.5s ease-out 0s;
          -moz-transition: all 0.5s ease-out 0s;
          -ms-transition: all 0.5s ease-out 0s;
          -o-transition: all 0.5s ease-out 0s;
          transition: all 0.5s ease-out 0s; }
</style>
