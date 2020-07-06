<template>
  <v-app>

    <app-header />
  
    <v-content>
     
      <v-container>
        <nuxt />
      </v-container>
    </v-content>

    <v-footer
      :fixed="fixed"
      app
    >
      <span>&copy; 2019</span>
    </v-footer>
  </v-app>
</template>

<script>
import AppHeader from '@/components/AppHeader.vue' 
export default {
  components:{
    AppHeader
  },
  data () {
    return {
      clipped: false,
      drawer: false,
      fixed: false,
      items: [
        {
          title: 'Welcome',
          to: '/'
        },
        {
          icon: 'mdi-chart-bubble',
          title: 'Inspire',
          to: '/inspire'
        }
      ],
      miniVariant: false,
      right: true,
      rightDrawer: false,
      title: 'Vuetify.js'
    }
  }
}
</script>
