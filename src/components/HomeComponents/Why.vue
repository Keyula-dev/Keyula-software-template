<template>
  <div>
      <v-row>
          <v-col cols="12" xs="12" sm="2" md="2" xl="2" lg="2" />
          <v-col cols="12" xs="12" sm="8" md="8" xl="8" lg="8">
              
              <section>
                  <p class="font-weight-bold blue--text lighten-3">Best software</p>
                  <p class="text-h4 font-weight-bold">Why choose us</p>
              </section>

             <v-row>
                 <v-col cols="12" xs="12" md="1" sm="1" lg="1" xl="1" />
                 <v-col cols="12" xs="12" md="10" sm="10" lg="10" xl="10">
                    <v-row>
                        <v-col cols="12" xs="12" md="6" sm="6" lg="6" xl="6" v-for="i in 4" :key="i.i">
                            <v-row>
                                <v-col cols="12" xs="4" sm="4" md="4" lg="4" xl="4">
                                    <v-icon size="30px" color="black">mdi-desktop-mac-dashboard</v-icon>
                                </v-col>
                                <v-col cols="8">
                                    hello woeld
                                </v-col>
                            </v-row>
                        </v-col>
                    </v-row>
                 </v-col>
                 <v-col cols="12" xs="12" md="1" sm="1" lg="1" xl="1" />
             </v-row>

          </v-col>
         
      </v-row>
  </div>
</template>

<script>
export default {

}
</script>

<style>

</style>