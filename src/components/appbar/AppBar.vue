<template>
  <v-app>
    <v-app-bar color="transparent">
    <v-avatar>
      <v-img :src="require('@/assets/logo.png')" large></v-img>
    </v-avatar>
      <v-spacer></v-spacer>
      <v-app-bar-nav-icon></v-app-bar-nav-icon>
    </v-app-bar>
  </v-app>
</template>

<script>
export default {
  name: "AppBar"
}
</script>

<style scoped>

</style>
