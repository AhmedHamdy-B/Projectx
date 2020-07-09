<template>
  <v-container>
      <v-card
    class="mx-auto event-card"
    max-width="400"
  >
    <v-img
      class="white--text d-flex   justify-end align-top"
      height="200px"
      :src="require('@/assets/imgs/meeting.jpg')"
    >
      <!-- <v-card-title class="d-flex  justify-end"><v-button class="Store">Top 10</v-button> </v-card-title> -->
            <v-button class="social d-flex  justify-center align-center px-5" >
      Social
    </v-button>
    </v-img>

    <v-card-subtitle cla > <v-button class="pb-0">Number 10</v-button> </v-card-subtitle>

    <v-card-text class="text--primary">
      <div>Whitehaven Beach</div>

      <div>Whitsunday Island, Whitsunday Islands</div>
    </v-card-text>

    <!-- <v-card-actions>
      <v-btn
        color="orange"
        text
      >
        Share
      </v-btn>

      <v-btn
        color="orange"
        text
      >
        Explore
      </v-btn>
    </v-card-actions> -->
  </v-card>
  </v-container>
</template>

<script>
export default {

}
</script>

<style>

</style>