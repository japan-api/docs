<template>
  <v-container>
    <v-row class="text-center">
      <v-col cols="12">
        <v-img :src="require('../assets/japan-logo.png')" class="my-3" contain height="200"/>
      </v-col>
      <v-col class="mb-4">
        <h1 class="display-2 font-weight-bold mb-3">
          Endpoints
        </h1>
      </v-col>
    </v-row>
     <v-breadcrumbs :items="items" class="red--text" large divider="|">
     </v-breadcrumbs>
  </v-container>
</template>

<script>
export default {
  name: 'EndpointsList',
  data: () => ({
    items: [
      {
        text: 'All',
        disabled: false,
        href: '#all',
      },
      {
        text: 'By Area Rank',
        disabled: false,
        href: '#area_rank/',
      },
      {
        text: 'By Population Rank',
        disabled: false,
        href: '#population_rank/',
      },
      {
        text: 'By ISO Code',
        disabled: false,
        href: '#iso_code/',
      },
      {
        text: 'Japan',
        disabled: false,
        href: '#japan',
      },
      {
        text: 'Hokkaido',
        disabled: false,
        href: '#hokkaido',
      },
      {
        text: 'Aomori',
        disabled: false,
        href: '#aomori',
      },
      {
        text: 'Iwate',
        disabled: false,
        href: '#iwate',
      },
      {
        text: 'Miyagi',
        disabled: false,
        href: '#miyagi',
      },
      {
        text: 'Akita',
        disabled: false,
        href: '#akita',
      },
      {
        text: 'Yamagata',
        disabled: false,
        href: '#yamagata',
      },
      {
        text: 'Fukushima',
        disabled: false,
        href: '#fukushima',
      },
      {
        text: 'Ibaraki',
        disabled: false,
        href: '#ibaraki',
      },
      {
        text: 'Tochigi',
        disabled: false,
        href: '#tochigi',
      },
      {
        text: 'Gunma',
        disabled: false,
        href: '#gunma',
      },
      {
        text: 'Saitama',
        disabled: false,
        href: '#saitama',
      },
      {
        text: 'Chiba',
        disabled: false,
        href: '#chiba',
      },
      {
        text: 'Tokyo',
        disabled: false,
        href: '#tokyo',
      },
      {
        text: 'Kanagawa',
        disabled: false,
        href: '#kanagawa',
      },
      {
        text: 'Niigata',
        disabled: false,
        href: '#niigata',
      },
      {
        text: 'Toyama',
        disabled: false,
        href: '#toyama',
      },
      {
        text: 'Ishikawa',
        disabled: false,
        href: '#ishikawa',
      },
      {
        text: 'Fukui',
        disabled: false,
        href: '#fukui',
      },
      {
        text: 'Yamanashi',
        disabled: false,
        href: '#yamanashi',
      },
      {
        text: 'Nagano',
        disabled: false,
        href: '#nagano',
      },
      {
        text: 'Gifu',
        disabled: false,
        href: '#gifu',
      },
      {
        text: 'Shizuoka',
        disabled: false,
        href: '#shizuoka',
      },
      {
        text: 'Aichi',
        disabled: false,
        href: '#aichi',
      },
      {
        text: 'Mie',
        disabled: false,
        href: '#mie',
      },
      {
        text: 'Shiga',
        disabled: false,
        href: '#shiga',
      },
      {
        text: 'Kyoto',
        disabled: false,
        href: '#kyoto',
      },
      {
        text: 'Osaka',
        disabled: false,
        href: '#osaka',
      },
      {
        text: 'Hyogo',
        disabled: false,
        href: '#hyogo',
      },
      {
        text: 'Nara',
        disabled: false,
        href: '#nara',
      },
      {
        text: 'Wakayama',
        disabled: false,
        href: '#wakayama',
      },
      {
        text: 'Tottori',
        disabled: false,
        href: '#tottori',
      },
      {
        text: 'Shimane',
        disabled: false,
        href: '#shimane',
      },
      {
        text: 'Okayama',
        disabled: false,
        href: '#okayama',
      },
      {
        text: 'Hiroshima',
        disabled: false,
        href: '#hiroshima',
      },
      {
        text: 'Yamaguchi',
        disabled: false,
        href: '#yamaguchi',
      },
      {
        text: 'Tokushima',
        disabled: false,
        href: '#tokushima',
      },
      {
        text: 'Kagawa',
        disabled: false,
        href: '#kagawa',
      },
      {
        text: 'Ehime',
        disabled: false,
        href: '#ehime',
      },
      {
        text: 'Kochi',
        disabled: false,
        href: '#kochi',
      },
      {
        text: 'Fukuoka',
        disabled: false,
        href: '#fukuoka',
      },
      {
        text: 'Saga',
        disabled: false,
        href: '#saga',
      },
      {
        text: 'Nagasaki',
        disabled: false,
        href: '#nagasaki',
      },
      {
        text: 'Kumamoto',
        disabled: false,
        href: '#kumamoto',
      },
      {
        text: 'Oita',
        disabled: false,
        href: '#oita',
      },
      {
        text: 'Miyazaki',
        disabled: false,
        href: '#miyazaki',
      },
      {
        text: 'Kagoshima',
        disabled: false,
        href: '#kagoshima',
      },
      {
        text: 'Okinawa',
        disabled: false,
        href: '#okinawa',
      },
    ],
  }),
};
</script>

<style>
.v-breadcrumbs__item {
  color: #f18282 !important;
}
</style>
