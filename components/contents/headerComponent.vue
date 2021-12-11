<template>
  <v-app-bar class="header-bar main">
    <v-toolbar-title class="header-title">
      <nuxt-link to="/">Vuetify</nuxt-link>
    </v-toolbar-title>
  </v-app-bar>
</template>

<script>
export default {
}
</script>

<style lang="scss" scoped>

.header-bar{
  background: #d7edff;
  position: fixed;
  top: 0;
  z-index: 5;
}
</style>
