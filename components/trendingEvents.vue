<template>
  <v-container>
      <v-row class="d-flex mt-12  justify-center trending--browse">
          <v-col class="d-flex  justify-center align-center" sm="6"  cols="6"><p class="trending--title">Trending Events</p></v-col>
          <v-col class="d-flex  justify-center align-center" sm="6" cols="6"><v-btn class="trending--browse" outlined color="primary">Browse All</v-btn></v-col>
      </v-row>
      <v-row>
        <v-col cols="12"  md="6" lg="3"  v-for="n in 20" :key="n.index">
      <EventCard/>

        </v-col>
      </v-row>
     
  </v-container>
</template>

<script>
export default {
 components: {
     EventCard: () => import('@/components/EventCard')
  }
}
</script>

<style>

</style>