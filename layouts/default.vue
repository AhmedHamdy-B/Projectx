<template>
  <v-app>
    <v-row>
      <v-col class="d-flex justify-center"  sm="12" md="8">
        <app-header  />
        
      </v-col>
      <v-col sm="4" class="pa-0 hidden-sm-and-down">
        <v-img class="header_Logo " :src="require('@/assets/imgs/pic1.jpg')" contain></v-img>
      </v-col>
    </v-row>

    <v-content>
      <v-container class="noPM">
        <nuxt />
      </v-container>
    </v-content>

  </v-app>
</template>

<script>
import AppHeader from "@/components/AppHeader.vue";
export default {
  components: {
    AppHeader
  },
  data() {
    return {
      clipped: false,
      drawer: false,
      fixed: false,
      items: [
        {
          title: "Welcome",
          to: "/"
        },
        {
          icon: "mdi-chart-bubble",
          title: "Inspire",
          to: "/inspire"
        }
      ],
      miniVariant: false,
      right: true,
      rightDrawer: false,
      title: "Vuetify.js"
    };
  }
};
</script>
