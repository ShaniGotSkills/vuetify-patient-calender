<template>

  <v-card>
     <v-row>
      <v-col cols="12" sm="4">
        <v-card color="#2784ff" class="rounded-lg px-2">
          <v-row>
            <v-col cols="12" sm="4">
              <v-avatar color="#dfedff">
                <v-img src="p.png"></v-img>
              </v-avatar>
            </v-col>

            <v-col cols="12" sm="8">
              <h4 class="white--text">Dev Cody</h4>
              <h6 class="white--text">25 years old</h6>
            </v-col>


            <v-col cols="12" sm="12" class="mt-3">
              <v-row>
                <v-col cols="12" sm="4">
                  <h6 class="grey--text text--lighten-4">Height</h6>
                  <h6 class="white--text">185</h6>
                </v-col>

                  <v-col cols="12" sm="4">
                  <h6 class="grey--text text--lighten-4">Weight</h6>
                  <h6 class="white--text">140</h6>
                </v-col>

                  <v-col cols="12" sm="4">
                  <h6 class="grey--text text--lighten-4">Blood Type</h6>
                  <h6 class="white--text">A+</h6>
                </v-col>
              </v-row>
            </v-col>
          </v-row>
        </v-card>
      </v-col>

   
      <v-col cols="12" sm="3">
        <v-card color="transparent" class="rounded-lg mx-2 px-2" flat>
          <span class="caption grey--text mt-6">Phone No.</span>
          <h5 class="black--text mb-7">+1 (490) 9943</h5>
          <span class="caption grey--text">Card Number</span>
          <h5 class="black--text">123456789</h5>
        </v-card>
      </v-col>

      <v-col cols="12" sm="5">
        <v-card color="transparent" class="rounded-lg px-2" flat> 
          <span class="caption grey--text mt-6">Email</span>
          <h5 class="black--text mb-7">cody@yahoo.com</h5>
          <span class="caption grey--text">Medical Condition</span>
          <h5 class="black--text">Asthma, Allergy</h5>
        </v-card>
      </v-col>
    </v-row>
    
  </v-card>

</template>

<script>
export default {

}
</script>

<style>

</style>