<template>
  <v-col cols="12">
    <v-card :id="prefectureName" class="mx-auto" max-width="460">
    <v-card-text>
      <div class="text-h5">{{ shortUrl + prefectureName }}</div>
      <p class="display-1 text--primary">
        {{ capitalizeFirst(prefectureName) }}
      </p>
      <p class="text-h7">GET request</p>
      <div class="text-h7 text--primary">
        {{ info + capitalizeFirst(prefectureName) }}
      </div>
    </v-card-text>
    <v-card-actions>
      <v-btn text color="pink lighten-1" class="mx-auto">
        <a class="pink--text text--lighten-1" :href="baseUrl + prefectureName" target="_blank">
          {{ noProtocolUrl + prefectureName.toUpperCase() }}
        </a>
      </v-btn>
    </v-card-actions>
  </v-card>
      </v-col>
</template>

<script>
export default {
  name: 'PrefectureInfo',
  props: ['prefectureName'],
  methods: {
    capitalizeFirst: (word) => word.charAt(0).toUpperCase() + word.slice(1),
  },
  data: () => ({
    baseUrl: 'https://japan-api.herokuapp.com/api/v1/',
    noProtocolUrl: 'japan-api.herokuapp.com/api/v1/',
    shortUrl: '/api/v1/',
    info: 'Info about',
  }),
};
</script>
