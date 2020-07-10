<template>
<v-app-bar app color="red lighten-4">
      <div class="d-flex align-center">
       <v-img alt="japan" class="shrink mr-2" contain src="../assets/japan-logo.png"
       transition="scale-transition" width="40"/>
        <h2 class="mr-2">{{ navbarTitle }}</h2>
      </div>
      <v-spacer></v-spacer>
      <v-btn :href="githubLink" target="_blank" text>
        <span class="text-lg-h6 mr-1">{{ githubTitle }}</span>
        <v-icon>{{ githubIcon }}</v-icon>
      </v-btn>
    </v-app-bar>
</template>

<script>
export default {
  name: 'Navbar',
  data: () => ({
    navbarTitle: 'Japan API',
    githubTitle: 'GitHub',
    githubIcon: 'mdi-github',
    githubLink: 'https://github.com/japan-api',
  }),
};
</script>
