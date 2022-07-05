<template>
  <v-app-bar
    style="padding:0px 90px:"
    app
    color="white"
    light
    elevation="6"
    elevate-on-scroll
  >
    <v-toolbar-title>iVote App</v-toolbar-title>
    <v-spacer />
    <v-list class="d-flex align-center">
      <v-list-item
        link
        v-for="(menu, index) in menus"
        :key="index"
        :to="menu.route"
      >
        <router-link>{{ menu.title }}</router-link>
      </v-list-item>

      <v-btn text>
        <v-icon>mdi-magnify</v-icon>
      </v-btn>
      <v-btn outlined color="success">Vote</v-btn>
    </v-list>
  </v-app-bar>
</template>

<script>
export default {
  name: "HeaderComp",
  data() {
    return {
      menus: [
        { title: "Home", route: "home" },
        { title: "Vote", route: "vote" },
        { title: "ContactUs", route: "contactUs" },

        { title: "Login", route: "login" },
      ],
    };
  },
};
</script>

<style scoped>
.v-toolbar__title {
  font-size: 32px;
  color: #4caf50;
  font-weight: 700;
  font-family: cursive;
}
</style>
