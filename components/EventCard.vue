<template>
  <v-container>
    <v-card class="mx-auto event-card">
      <v-img
        class="white--text d-flex justify-end align-top"
        height="15rem"
        :src="require('@/assets/imgs/meeting.jpg')"
      >
        <!-- <v-card-title class="d-flex  justify-end"><v-button class="Store">Top 10</v-button> </v-card-title> -->
        <v-button class="social d-flex justify-center align-center px-5">Social</v-button>
      </v-img>

      <v-row class="pb-8">
        <v-col cols="8" class="d-flex pl-8 pt-5 flex-column justify-start align-start">
          <p class="body-2 font-weight-black">Social Conference</p>
          <span class="font-weight-light text__grey">KSA-Riyadh</span>
          <span class="font-weight-light text__grey">Monday 4:00 Pm</span>
        </v-col>
        
        <v-col cols="4" class="d-flex  justify-end align-top">
            <div   class="px-5 py-8 d-flex flex-column justify-center align-center date__button mr-5">
              <span class="d-block mt-2 p-0 headline "> 25</span>
              <span class="d-block mb-2 p-0 font-weight-light ">June</span>
            </div>
         </v-col>
      </v-row>
      <!-- <v-card-subtitle cla > <v-button class="pb-0">Number 10</v-button> </v-card-subtitle>

    <v-card-text class="text--primary">
      <div>Whitehaven Beach</div>

      <div>Whitsunday Island, Whitsunday Islands</div>
      </v-card-text>-->

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
      </v-card-actions>-->
    </v-card>
  </v-container>
</template>

<script>
export default {};
</script>

<style>
</style>