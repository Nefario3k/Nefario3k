<template>
  <v-app light color="white" style="background: white">
    <v-app-bar fixed class="bg-dark" elevate-on-scroll>
      <v-toolbar-title>Title</v-toolbar-title>
      <v-spacer></v-spacer>
      <nav class="navbar navbar-expand-lg">
        <ul class="navbar-nav text-uppercase">
          <li class="nav-item">
            <nuxt-link class="nav-link" to="/#">Home</nuxt-link>
          </li>
          <li class="nav-item">
            <nuxt-link class="nav-link" to="/#about">About</nuxt-link>
          </li>
          <li class="nav-item">
            <nuxt-link class="nav-link" to="/#projects">Projects</nuxt-link>
          </li>
          <li class="nav-item">
            <nuxt-link class="nav-link" to="/#skillset">Skill Sets</nuxt-link>
          </li>
          <li class="nav-item">
            <nuxt-link class="nav-link" to="/">Contact</nuxt-link>
          </li>
        </ul>
      </nav></v-app-bar
    >

    <v-main class="main">
      <Nuxt />
    </v-main>
  </v-app>
</template>

<script>
export default {}
</script>

<style scoped>
</style>