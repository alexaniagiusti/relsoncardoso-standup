<template>
  <div style="background-color: #CFD8DC">
    <h1
      style="font-family: 'Asap', sans-serif; color: #455A64; text-align:center; padding:10px; font-size: 20pt; text-decoration: underline"
    >BIOGRAFIA</h1>
    <div class="container stretch">
      <v-row>
        <v-col class="item" cols="12" md="6" xs="12">
          <v-img width="800" src="../assets/img/FOTO.png"></v-img>
        </v-col>
        <v-col class="item" cols="12" md="6" xs="12">
          <h2
            style="font-family: 'Asap', sans-serif;color: #455A64; text-align:center;"
          >Como comecei?</h2>
          <p class="paragrafo">
            Iniciou a sua trajetória no Stand Up em abril de 2019 em um evento denominado Circuito cultural,
            de lá pra cá não parou mais. Fez a abertura do segundo show de Hulk Pão no teatro das bacabeiras,
            fez diversos eventos cooporativos, lotou uma casa de shows em Santana juntamente com o grupo Liga
            da Comédia, onde é um dos fundadores e dividiu por duas noites o palco do teatro das Bacabeiras com
            os integrantes do grupo de comédia mais badalado de Belém do Pará, o panelinha 2.0.
          </p>
          <p class="paragrafo">
            Sempre escreveu textos relatando situações do cotidiano carregados de muito bom
            humor, nem imaginava que estava produzindo um material na estrutura do Stand Up Comedy. Quando se interessou
            pelo assunto e começou a pesquisar a parte técnica desse seguimento da comédia, percebeu os
            textos q escrevia desde muito tempo nada mais eram do que criações no modelo Stand Up.
          </p>
          <p class="paragrafo">
            Após uma conversa que teve com o amigo Joabe Silva em sua residência, decidiu que deveria encontrar uma maneira
            de mostrar para as outras pessoas os seus textos através de uma apresentação, foi aí que tiveram a ideia
            de formar o grupo humoristico Liga da Comédia, coincidentemente nessa mesma época, iria acontecer em Santana
            uma espécie de festival de talentos, o grupo foi convidado pelo organizador para fazer uma apresentação
            nesse dia, apesar do pouco tempo que tiveram para se preparar, a estreia foi um sucesso de criticas.
          </p>
          <p class="paragrafo">
            Alguns meses depois o grupo teve um evento na principal casa de shows de Santana, com os ingressos esgotados,
            o Liga da Comédia realizou um grande show, com textos 100% autorais entrerteram a platéia durante toda a
            apresentação. Mais uma vez os elogios se fizeram presentes, logo após o evento, Relson Cardoso decide sair
            do grupo para focar em projetos solos, mas sempre contando com o apoio dos outros integrantes.
            Os convites para apresentações continuaram surgindo e percebeu-se a necessidade de criar um show
            bem mais elaborado e com mais tempo de apresentação, após alguns meses escrevendo
            e produzindo material inédito, Relson Cardoso anuncia para o inicio de 2020 o seu show solo intitulado, "Como Eu Vejo O Mundo".
          </p>
        </v-col>
      </v-row>
    </div>
  </div>
</template>

<style scoped>
/* Flex Container */
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
  text-align: center;
  font-size: 12 pt;
}

.paragrafo {
  font-family: "Asap", sans-serif;
  text-align: justify;
  padding: 5px;
  font-size: 12pt;
}
</style>
