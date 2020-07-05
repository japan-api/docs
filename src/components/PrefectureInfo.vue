<template>
  <v-col cols="12">
    <v-card :id="prefectureName" class="mx-auto" max-width="440">
    <v-card-text>
      <div class="text-h5">/api/v1/{{ prefectureName }}</div>
      <p class="display-1 text--primary">
        {{ capitalizeFirst(prefectureName) }}
      </p>
      <p class="text-h7">GET request</p>
      <div class="text-h7 text--primary">
       Info about {{ capitalizeFirst(prefectureName) }} itself
      </div>
    </v-card-text>
    <v-card-actions>
      <v-btn text color="red lighten-1" class="mx-auto">
        <a class="red--text text--lighten-2" :href="baseUrl + prefectureName" target="_blank">
          japanapi.pythonanywhere.com/api/v1/{{ prefectureName.toUpperCase() }}
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
    baseUrl: 'https://japanapi.pythonanywhere.com/api/v1/',
  }),
};
</script>
