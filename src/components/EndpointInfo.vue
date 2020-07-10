<template>
  <v-col cols="12">
    <v-card :id="endpointName" class="mx-auto" max-width="510">
    <v-card-text>
      <div class="text-h5">{{ shortUrl + endpointFullName }}</div>
      <p class="display-1 text--primary">
        {{ capitalizeFirst(endpointType) }}
      </p>
      <p class="text-h7">GET request</p>
      <div class="text-h7 text--primary">
       {{ endpointInfo }}
      </div>
    </v-card-text>
    <v-card-actions>
      <v-btn text color="red lighten-1" class="mx-auto">
        <a class="red--text text--lighten-2" :href="baseUrl + endpointName" target="_blank">
          {{ noProtocolUrl + endpointName.toUpperCase() }}
        </a>
      </v-btn>
    </v-card-actions>
  </v-card>
      </v-col>
</template>

<script>
export default {
  name: 'EndpointInfo',
  props: ['endpointName', 'endpointFullName', 'endpointInfo', 'endpointType'],
  methods: {
    capitalizeFirst: (word) => word.charAt(0).toUpperCase() + word.slice(1),
  },
  data: () => ({
    baseUrl: 'https://japanapi.pythonanywhere.com/api/v1/',
    noProtocolUrl: 'japanapi.pythonanywhere.com/api/v1/',
    shortUrl: '/api/v1/',
  }),
};
</script>
