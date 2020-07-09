<template>
  <v-container class="noPM  " ma-0 pa-0
  >
  <div class="EventPlus">
     <p class="headline font-weight-medium d-flex justify-center  pt-12">Events Plus</p>
   <v-row class="px-12 pt-2 ma-0 d-flex  justify-space-between " >
    <v-col sm="4" class="pa-5 ma-0 d-flex flex-column justify-center align-center">
       <v-img class="EventImgs pr-5" :src="require('@/assets/imgs/clock.png')" aspect-ratio="1.7" contain></v-img>   

        <p class="  d-flex justify-left event-title">Planning</p>
        <span class="  d-flex justify-left desc">Great minds Discuss Ideas</span>
    </v-col> <v-col sm="4" class="pa-5 ma-0 d-flex  flex-column justify-center align-center">
       <v-img class="EventImgs d-flex justify-center" :src="require('@/assets/imgs/house.png')" aspect-ratio="1.7" contain></v-img>   

        <p class="  d-flex justify-center event-title">Organize</p>
        <span class="  d-flex justify-left desc ">Great minds Discuss Ideas</span>

    </v-col> <v-col sm="4" class="pa-5 ma-0 d-flex flex-column justify-center align-center">
       <v-img class="EventImgs" :src="require('@/assets/imgs/group.png')" aspect-ratio="1.7" contain></v-img>   

        <p class="  d-flex justify-center event-title">Store</p>
        <span class="  d-flex justify-left desc">Great minds Discuss Ideas</span>

    </v-col>
  </v-row>
  </div>
  <trendingEvents/>
  </v-container>
</template>

<script>
export default {
  components: {
     trendingEvents: () => import('@/components/trendingEvents')
  }
}
</script>
