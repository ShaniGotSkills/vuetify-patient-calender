<template>
  <v-app
    id="inspire"
    :style="{ background: $vuetify.theme.themes.dark.background }"
  >
    <Sidebar />
    <Navbar />
    <v-container>
      <v-row>
        <v-col cols="12" sm="9">
          <v-row>
            <v-col cols="12" sm="12">
              <Contact />
            </v-col>
            <v-col cols="12" sm="12">
            <Agenda />
            </v-col>
          </v-row>
        </v-col>
        <v-col cols="12" sm="3">
            <Doctor />
        </v-col>
      </v-row>
    </v-container>
  </v-app>
</template>


<script>
  import Navbar from '../components/Navbar'
  import Sidebar from '../components/Sidebar'
  import Agenda from '../components/Agenda'
  import Contact from '../components/Contact'
  import Doctor from '../components/Doctor'

  export default {
    name: 'Home',

    components: {
      Sidebar,
    Navbar,
    Contact,
    Agenda,
    Doctor
    },
  }
</script>
