<template>
<v-app-bar app color="red lighten-4">
      <div class="d-flex align-center">
       <v-img alt="japan" class="shrink mr-2" contain src="../assets/japan-logo.png"
       transition="scale-transition" width="40"/>
        <h2 class="mr-2">Japan API</h2>
      </div>
      <v-spacer></v-spacer>
      <v-btn href="https://github.com/irevenko/japan-api" target="_blank" text>
        <span class="text-lg-h6 mr-1">GitHub</span>
        <v-icon>mdi-github</v-icon>
      </v-btn>
    </v-app-bar>
</template>

<script>
export default {
  name: 'Navbar',
};
</script>
