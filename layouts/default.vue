<template>
  <v-app>
    <headerComponent />
    <nuxt />
  </v-app>
</template>

<script>
import headerComponent from '~/components/template/headerComponent'

export default {
  name: 'default',
  components: {
    headerComponent
  }
}
</script>
