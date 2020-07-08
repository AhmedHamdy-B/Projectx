<template>
  <v-container class="noPM" ma-0 pa-0
  >
  <div class="EventPlus">
     <p class="headline font-weight-medium d-flex justify-center">Events Plus</p>
   <v-row class="pa-0 ma-0 d-flex justify-center " >
    <v-col sm="4" class="pa-0 ma-0 d-flex flex-column justify-center">
       <v-img class="EventImgs" :src="require('@/assets/imgs/clock.png')" aspect-ratio="1.7" contain></v-img>   

        <h2>weblalalal</h2>
    </v-col> <v-col sm="4" class="pa-0 ma-0 d-flex  flex-column justify-center">
       <v-img class="EventImgs" :src="require('@/assets/imgs/house.png')" aspect-ratio="1.7" contain></v-img>   

        <p>weblalalal</p>
    </v-col> <v-col sm="4" class="pa-0 ma-0 d-flex flex-column justify-center">
       <v-img class="EventImgs" :src="require('@/assets/imgs/group.png')" aspect-ratio="1.7" contain></v-img>   

        <p>weblalalal</p>
    </v-col>
  </v-row>
  </div>
  
  </v-container>
</template>

<script>

export default {
  components: {
  }
}
</script>
