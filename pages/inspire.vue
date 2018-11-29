<template>
  <v-layout>
    <v-flex text-xs-center>
      <Container :data="data"/>
    </v-flex>
  </v-layout>
</template>

<script>
import Container from '../components/Container'
import data from '../static/data.json'

export default {
  name: 'Home',
  components: {
    Container
  },
  data() {
    return {
      data
    }
  }
}
</script>
