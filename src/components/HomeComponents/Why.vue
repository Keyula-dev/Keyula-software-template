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
                        <v-col cols="12" xs="12" md="6" sm="6" lg="6" xl="6" v-for="i in why" :key="i.i">
                            <v-row align="center">
                                <v-col cols="12" xs="4" sm="4" md="4" lg="4" xl="4">
                                    <v-icon size="70px" color="blue lighten-2">{{i.icon}}</v-icon>
                                </v-col>
                                <v-col cols="8">
                                    <p class="font-weight-bold">{{i.title}}</p>
                                    <p class="text-caption grey--text darken-3--text">{{i.desc}}</p>
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
    data(){
        return{
            why:[
                {title:'Elegant and Modern Design',desc:'The designs we make are designsthat are trending. Our teammakes sure your website always look good',icon:'mdi-desktop-mac-dashboard'},
                {title:'Data is always safe',desc:'We finally found a host that truly understoodthe unique secure iona need to know basis found a host that truly knows',icon:' mdi-credit-card-search'},
                {title:'High-End Analysing',desc:'Share processes and data secure iona needto know basis. Our team assured your web site is always safe and secure',icon:'mdi-set-all'},
                {title:'Our Dedicated support',desc:'Share processes and data secure iona need to know basis. Our team assured your web site is always safe and secure',icon:'mdi-map-minus'},
                
            ]
        }
    }
}
</script>

<style>

</style>