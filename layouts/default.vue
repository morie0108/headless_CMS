<template>
  <v-app>
    <headerComponent />
    <nuxt />
  </v-app>
</template>

<script>
import headerComponent from '~/components/contents/headerComponent'

export default {
  name: 'default',
  components: {
    headerComponent
  }
}
</script>
