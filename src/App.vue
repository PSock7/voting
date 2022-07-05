<template>
  <v-app>
    <router-view />
    <HeaderComp />
    <v-main>
      <!-- Hero section -->
      <HeroComponent />
      <!-- About us -->
      <ContactUs />
      <!-- Candidat section -->
      <CandidatComp />
      <!-- Statistique section -->
      <StatsComp />
      <!--  Vote section -->
      <VoteComp />
      <LoginComp />
    </v-main>
  </v-app>
</template>

<script>
import HeaderComp from "./components/HeaderComp.vue";
import HeroComponent from "./components/HeroComponent.vue";
import ContactUs from "./components/ContactUs.vue";
import CandidatComp from "./components/CandidatComp.vue";
import StatsComp from "./components/StatsComp.vue";
import VoteComp from "./components/VoteComp.vue";
import LoginComp from "./components/LoginComp.vue";
export default {
  name: "App",
  components: {
    HeaderComp,
    HeroComponent,
    ContactUs,
    CandidatComp,
    StatsComp,
    VoteComp,
    LoginComp,
  },
};
//
</script>
