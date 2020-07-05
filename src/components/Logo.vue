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
     <v-breadcrumbs :items="items"
     class="red--text" large divider="|">
     </v-breadcrumbs>
  </v-container>
</template>

<script>
export default {
  name: 'Logo',
  data: () => ({
    items: [
      {
        text: 'All',
        disabled: false,
        href: '#prefecture-anchor',
      },
      {
        text: 'By Area Rank',
        disabled: false,
        href: 'breadcrumbs_link_1',
      },
      {
        text: 'By Population Rank',
        disabled: false,
        href: 'breadcrumbs_link_1',
      },
      {
        text: 'By ISO Code',
        disabled: false,
        href: 'breadcrumbs_link_1',
      },
      {
        text: 'Japan',
        disabled: false,
        href: 'breadcrumbs_link_1',
      },
      {
        text: 'Hokkaido',
        disabled: false,
        href: '#hokkaido',
      },
      {
        text: 'Aomori',
        disabled: false,
        href: 'breadcrumbs_link_1',
      },
      {
        text: 'Iwate',
        disabled: false,
        href: 'breadcrumbs_link_1',
      },
      {
        text: 'Miyagi',
        disabled: false,
        href: 'breadcrumbs_link_1',
      },
      {
        text: 'Akita',
        disabled: false,
        href: 'breadcrumbs_link_1',
      },
      {
        text: 'Yamagata',
        disabled: false,
        href: 'breadcrumbs_link_1',
      },
      {
        text: 'Fukushima',
        disabled: false,
        href: 'breadcrumbs_link_1',
      },
      {
        text: 'Ibaraki',
        disabled: false,
        href: 'breadcrumbs_link_1',
      },
      {
        text: 'Tochigi',
        disabled: false,
        href: 'breadcrumbs_link_1',
      },
      {
        text: 'Gunma',
        disabled: false,
        href: 'breadcrumbs_link_1',
      },
      {
        text: 'Saitama',
        disabled: false,
        href: 'breadcrumbs_link_1',
      },
      {
        text: 'Chiba',
        disabled: false,
        href: 'breadcrumbs_link_1',
      },
      {
        text: 'Tokyo',
        disabled: false,
        href: '#tokyo',
      },
      {
        text: 'Kanagawa',
        disabled: false,
        href: '#prefecture-anchor',
      },
      {
        text: 'Niigata',
        disabled: false,
        href: 'breadcrumbs_link_1',
      },
      {
        text: 'Toyama',
        disabled: false,
        href: 'breadcrumbs_link_1',
      },
      {
        text: 'Ishikawa',
        disabled: false,
        href: 'breadcrumbs_link_1',
      },
      {
        text: 'Fukui',
        disabled: false,
        href: 'breadcrumbs_link_1',
      },
      {
        text: 'Yamanashi',
        disabled: false,
        href: 'breadcrumbs_link_1',
      },
      {
        text: 'Nagano',
        disabled: false,
        href: 'breadcrumbs_link_1',
      },
      {
        text: 'Gifu',
        disabled: false,
        href: 'breadcrumbs_link_1',
      },
      {
        text: 'Shizuoka',
        disabled: false,
        href: 'breadcrumbs_link_1',
      },
      {
        text: 'Aichi',
        disabled: false,
        href: 'breadcrumbs_link_1',
      },
      {
        text: 'Mie',
        disabled: false,
        href: 'breadcrumbs_link_1',
      },
      {
        text: 'Shiga',
        disabled: false,
        href: 'breadcrumbs_link_1',
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
        href: 'breadcrumbs_link_1',
      },
      {
        text: 'Nara',
        disabled: false,
        href: 'breadcrumbs_link_1',
      },
      {
        text: 'Wakayama',
        disabled: false,
        href: 'breadcrumbs_link_1',
      },
      {
        text: 'Tottori',
        disabled: false,
        href: 'breadcrumbs_link_1',
      },
      {
        text: 'Shimane',
        disabled: false,
        href: 'breadcrumbs_link_1',
      },
      {
        text: 'Okayama',
        disabled: false,
        href: 'breadcrumbs_link_1',
      },
      {
        text: 'Hiroshima',
        disabled: false,
        href: 'breadcrumbs_link_1',
      },
      {
        text: 'Yamaguchi',
        disabled: false,
        href: 'breadcrumbs_link_1',
      },
      {
        text: 'Tokushima',
        disabled: false,
        href: 'breadcrumbs_link_1',
      },
      {
        text: 'Kagawa',
        disabled: false,
        href: 'breadcrumbs_link_1',
      },
      {
        text: 'Ehime',
        disabled: false,
        href: 'breadcrumbs_link_1',
      },
      {
        text: 'Kochi',
        disabled: false,
        href: 'breadcrumbs_link_1',
      },
      {
        text: 'Fukuoka',
        disabled: false,
        href: 'breadcrumbs_link_1',
      },
      {
        text: 'Saga',
        disabled: false,
        href: 'breadcrumbs_link_1',
      },
      {
        text: 'Nagasaki',
        disabled: false,
        href: 'breadcrumbs_link_1',
      },
      {
        text: 'Kumamoto',
        disabled: false,
        href: 'breadcrumbs_link_1',
      },
      {
        text: 'Oita',
        disabled: false,
        href: 'breadcrumbs_link_1',
      },
      {
        text: 'Miyazaki',
        disabled: false,
        href: 'breadcrumbs_link_1',
      },
      {
        text: 'Kagoshima',
        disabled: false,
        href: 'breadcrumbs_link_1',
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
