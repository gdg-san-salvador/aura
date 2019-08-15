<template>
  <v-content class="pa-0">

    <v-container fluid class="mt-3 mb-0">
      <v-layout wrap align-center justify-center row fill-height class="my-0">
        <v-flex xs12 md10 class="my-0">
            <p class="google-font mb-0" style="font-size:200%;color:#616161">Nuestra alineaci&oacute;n de grandes pensadores.</p>
            <p class="google-font mt-0 mb-0" style="font-size:110%">Google es conocido en todo el mundo. Todos buscan con Google, navegan con Google Maps y se escriben por Gmail... Para el usuario final, estos son servicios que simplemente y sencillamente funcionan, pero no para nosotros. Los desarrolladores vemos mucho m&aacute;s: el c&oacute;digo fuente, lenguaje de programaci&oacute;n, APIs, problemas de escalabilidad, UI, UX, Graphic Design, tech stacks complejos, algoritmos, etc... y de eso se trata el GDG.</p>
            <p class="google-font mt-3 mb-0" style="font-size:110%">Nuestro objetivo es organizar un espacio y un canal para conectar a los mejores expertos de la industria con la audiencia de San Salvador y sus alrededores, para impulsar el desarrollo personal y profesional de personas de todas las edades mediante el uso apropiado de la tecnolog&iacute;a.</p>
        </v-flex>
      </v-layout>
    </v-container>

    <v-container fluid >
      <v-layout wrap align-center justify-center row fill-height>
        <v-flex xs12 md10 class="">
          <coreTeam/>
        </v-flex>
      </v-layout>
    </v-container>

    <v-container fluid >
      <v-layout wrap align-center justify-center row fill-height>
        <v-flex xs12 md10 class="">
          <organizingTeam/>
        </v-flex>
      </v-layout>
    </v-container>

  </v-content>

</template>

<script>
import TeamDetails from '@/assets/data/chapterDetails.json'
import coreTeam from '@/components/team/coreTeam'
import organizingTeam from '@/components/team/organizingTeam'
  export default {
    components: {
      coreTeam,
      organizingTeam
    },
    data() {
      return {
        TeamDetails: TeamDetails,
      }
    },
  }
</script>
