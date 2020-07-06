<template>
  <v-container>
       <v-toolbar flat>
      <v-app-bar-nav-icon></v-app-bar-nav-icon>

      <v-toolbar-title>Title</v-toolbar-title>

      <v-spacer></v-spacer>

      <NuxtLink class="headerItems" to="/categories">
     Categories
    </NuxtLink>

       <NuxtLink to="/events">
      Events
    </NuxtLink>

      <NuxtLink to="/store">
      Store
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