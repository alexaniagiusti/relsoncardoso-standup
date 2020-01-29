<template>
<div>

  <div class="topo-desktop hidden-sm-and-down">
    <v-app-bar
    elevation="0"
    color="indigo lighten-5"
    dense
    >
      <v-toolbar-title style="font-family: 'Handlee', cursive; font-size: 19pt; color: #455A64">Relson Cardoso</v-toolbar-title>

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
            <li><a class="page_scroll" href="#"><span style="font-size: 20pt" class="mdi mdi-facebook-box"></span></a></li>
            <li><a class="page_scroll" href="#"><span style="font-size: 20pt" class="mdi mdi-instagram"></span></a></li>
            <li><a class="page_scroll" href="#"><span style="font-size: 20pt" class="mdi mdi-whatsapp"></span></a></li>
          </ul>
        </nav>
      </div>
    </v-app-bar>
    <v-card
      class="mx-auto"
      height="300"
    >
      <v-img
        class="white--text align-end"
        height="400px"
        src="../assets/img/capa.png"
      >
      </v-img>
  </v-card>
  </div>
  <div class="mobile_menu">
    <div class="row align-items-center mobile_header">
      <div class="col-lg-3 col-md-4 col-6">
        <div class="brand_logo">
          <a href="index.html"><img src="assets/images/logo_2.png" class="img-fluid" alt=""></a>
        </div>
      </div>
      <div class="col-lg-9 col-md-8 col-6">
        <div class="menu_button">
          <div class="menu_icon">
            <span></span>
            <span></span>
            <span></span>
          </div>
        </div>
      </div>
    </div>
    <div class="sidenav_menu">
      <div class="close_icon">
        <a href="#" class="close_btn"><i class="fas fa-times"></i></a>
      </div>
      <ul class="sidebar-menu">
        <li class="active"><a class="page_scroll" href="#home">Início</a></li>
        <li><a class="page_scroll" href="#about">Sobre</a></li>
        <li><a class="page_scroll" href="#service">Serviços</a></li>
        <li><a class="page_scroll" href="#portfolio">Projetos</a></li>
        <li><a class="page_scroll" href="#blog">Blog</a></li>
        <li><a class="page_scroll" href="#contact">Contato</a></li>
      </ul>
    </div>
  </div>
</div>

</template>

<style scoped>
.primary_menu .main_menu ul li {
        display: inline-block;
        margin-left: 25px;
        -webkit-transition: all 0.4s ease-out 0s;
        -moz-transition: all 0.4s ease-out 0s;
        -ms-transition: all 0.4s ease-out 0s;
        -o-transition: all 0.4s ease-out 0s;
        transition: all 0.4s ease-out 0s; }

.primary_menu .main_menu ul li a {
          font-size: 15px;
          color: #455A64;
          display: block;
          padding: 42px 0;
          font-family: "Quicksand", sans-serif;
          text-transform: uppercase;
          text-decoration: none;
          font-weight: 600;
          -webkit-transition: all 0.5s ease-out 0s;
          -moz-transition: all 0.5s ease-out 0s;
          -ms-transition: all 0.5s ease-out 0s;
          -o-transition: all 0.5s ease-out 0s;
          transition: all 0.5s ease-out 0s; }
.primary_menu .main_menu ul li a:hover {
            color: #303F9F; }
</style>
