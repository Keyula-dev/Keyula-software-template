<template>
  <div class="home">
    <Why />
    <br>
    <br>
  
    <v-row align="center" justify="center">
      <v-col cols="1" xs="12" sm="2" md="2" lg="1" xl="1" />
      <v-col cols="10" xs="12" sm="8" md="8" lg="8" xl="8">
        <Best />
      </v-col>
      <v-col cols="1" xs="12" sm="1" md="1" lg="1" xl="1" />
    </v-row>
    
  </div>
</template>

<script>
// @ is an alias to /src
import Why from '../components/HomeComponents/Why'
import Best from '../components/HomeComponents/Best'

export default {
  name: 'Home',
  components: {
    Why,
    Best
  }
}
</script>
