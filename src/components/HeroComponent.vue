<template>
  <v-container>
    <v-row>
      <v-col lg="6">
        <h2 class="intro-text">Welcome to our iVote App</h2>
        <p class="description">
          Bienvenue dans notre site de vote en ligne,veuiller cliquer sur le
          bouton renvoyant une video d'explication du site et la procédure de
          vote
        </p>
        <v-btn color="success" class="white--text" rounded>Vote</v-btn>
        <v-btn color="indigo" class="white--text" rounded>
          <v-icon>mdi-play-circle</v-icon>
        </v-btn>
      </v-col>
      <v-col lg="6">
        <img width="100%" src="./../assets/2.svg" alt="" />
      </v-col>
    </v-row>
  </v-container>
</template>

<script>
export default {};
</script>

<style scoped>
h2.intro-text {
  font-size: 60px;
  font-weight: bold;
  font-family: cursive;
  color: #444;
}
p.description {
  font-size: 19px;
  font-family: cursive;
  margin: 32px 0px;
  color: #444444ba;
}
</style>
