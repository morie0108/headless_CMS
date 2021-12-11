<template>
  <v-app>
    <headerComponent />
    <nuxt />
    <footerComponent />
  </v-app>
</template>

<script>
import headerComponent from '~/components/contents/headerComponent'
import footerComponent from '~/components/contents/footerComponent'

export default {
  name: 'default',
  components: {
    headerComponent,
    footerComponent
  }
}
</script>
