<template>
  <v-container>
    <v-row class="text-center">
      <v-col cols="12" class="mt-10">
        <v-img :src="require('../assets/japan-logo.png')" class="my-3" contain height="200"/>
      </v-col>
      <v-col class="mb-4">
        <h1 class="display-2 font-weight-bold mb-3">
          {{ title }}
        </h1>
      </v-col>
    </v-row>
     <v-breadcrumbs id="list" :items="items" large divider="|">
     </v-breadcrumbs>
  </v-container>
</template>

<script>
import endpoints from '../../utils/endpoints';

export default {
  name: 'EndpointsList',
  data: () => ({
    items: endpoints,
    title: 'Endpoints',
  }),
};
</script>

<style>
.v-breadcrumbs__item {
  color: #F06292 !important;
}
</style>
