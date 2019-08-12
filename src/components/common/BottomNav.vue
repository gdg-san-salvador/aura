<template>
  <v-card color="white" height="60px" class="white hidden-sm-and-up" flat>
    <v-bottom-nav
      :active.sync="bottomNav"
      :value="true"
      app
      color="white"
      class="elevation-2"

    >
      <v-btn
        color="#518FF5"
        flat
        value="home"
        router
        to="/home"
      >
        <span>Inicio</span>
        <v-icon>dashboard</v-icon>
      </v-btn>

      <v-btn
        color="#518FF5"
        flat
        value="events"
        router
        to="/events"
      >
        <span>Eventos</span>
        <v-icon>rounded_corner</v-icon>
      </v-btn>

      <v-btn
        color="#518FF5"
        flat
        value="team"
        router
        to="/team"
      >
        <span>Equipo</span>
        <v-icon>group</v-icon>
      </v-btn>

      <v-btn
        color="#518FF5"
        flat
        value="about"
        router
        to="/about"
      >
        <span>Acerca de</span>
        <v-icon>toc</v-icon>
      </v-btn>



      <!-- <v-btn
        color="#518FF5"
        flat
        value="contact"
        router
        to="/contact"
      >
        <span>Cont&aacute;tanos</span>
        <v-icon>person</v-icon>
      </v-btn> -->

    </v-bottom-nav>
  </v-card>
</template>


<script>
  export default {
    data () {
      return {
        bottomNav: 'recent',
        items: [
            { title: 'Inicio', icon: 'dashboard', route:"/home" },
            { title: 'Asiste', icon: 'rounded_corner', route:"/attending" },
            { title: 'Sesiones', icon: 'toc', route:"/sessions" },
            { title: 'Speakers', icon: 'group', route:"/speakers" }
        ],
      }
    }
  }
</script>
