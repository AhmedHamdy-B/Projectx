<template>
  <v-container>
    
       <v-toolbar class="my-toolbar d-flex justify-left" flat>
        

      <NuxtLink class="Home" to="/">
     Home
    </NuxtLink>
       <NuxtLink class="Events" to="/events">
      Events
    </NuxtLink>

      <NuxtLink class="Store" to="/store">
      Store
    </NuxtLink>
          <NuxtLink class="Categories" to="/categories">
     Categories
    </NuxtLink>
    </v-toolbar>

  </v-container>
</template>

<script>
export default {

}
</script>

<style>

</style>