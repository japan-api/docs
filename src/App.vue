<template>
  <v-app>
      <Navbar/>
      <EndpointsList/>
      <EndpointInfo
      endpoint-name="all"
      endpoint-full-name="all"
      endpoint-info="List of all prefectures (including Japan)"
      endpoint-type="all prefectures"/>
      <EndpointInfo
      endpoint-name="area_rank/"
      endpoint-full-name="area_rank/int:area_rank"
      endpoint-info="Find by area rank (among all prefectures)"
      endpoint-type="by area rank"/>
      <EndpointInfo
      endpoint-name="population_rank/"
      endpoint-full-name="population_rank/int:population_rank"
      endpoint-info="Find by population rank (among all prefectures)"
       endpoint-type="by population rank"/>
      <EndpointInfo
      endpoint-name="iso_code/"
      endpoint-full-name="iso_code/int:prefecture_iso"
      endpoint-info="Find by ISO Code (among all prefectures)"
      endpoint-type="by ISO Code"/>
      <PrefectureInfo prefecture-name="japan"/>
      <PrefectureInfo prefecture-name="hokkaido"/>
      <PrefectureInfo prefecture-name="aomori"/>
      <PrefectureInfo prefecture-name="iwate"/>
      <PrefectureInfo prefecture-name="miyagi"/>
      <PrefectureInfo prefecture-name="akita"/>
      <PrefectureInfo prefecture-name="yamagata"/>
      <PrefectureInfo prefecture-name="fukushima"/>
      <PrefectureInfo prefecture-name="ibaraki"/>
      <PrefectureInfo prefecture-name="tochigi"/>
      <PrefectureInfo prefecture-name="gunma"/>
      <PrefectureInfo prefecture-name="saitama"/>
      <PrefectureInfo prefecture-name="chiba"/>
      <PrefectureInfo prefecture-name="tokyo"/>
      <PrefectureInfo prefecture-name="kanagawa"/>
      <PrefectureInfo prefecture-name="niigata"/>
      <PrefectureInfo prefecture-name="toyama"/>
      <PrefectureInfo prefecture-name="ishikawa"/>
      <PrefectureInfo prefecture-name="fukui"/>
      <PrefectureInfo prefecture-name="yamanashi"/>
      <PrefectureInfo prefecture-name="nagano"/>
      <PrefectureInfo prefecture-name="gifu"/>
      <PrefectureInfo prefecture-name="shizuoka"/>
      <PrefectureInfo prefecture-name="aichi"/>
      <PrefectureInfo prefecture-name="mie"/>
      <PrefectureInfo prefecture-name="shiga"/>
      <PrefectureInfo prefecture-name="kyoto"/>
      <PrefectureInfo prefecture-name="osaka"/>
      <PrefectureInfo prefecture-name="hyogo"/>
      <PrefectureInfo prefecture-name="nara"/>
      <PrefectureInfo prefecture-name="wakayama"/>
      <PrefectureInfo prefecture-name="tottori"/>
      <PrefectureInfo prefecture-name="shimane"/>
      <PrefectureInfo prefecture-name="okayama"/>
      <PrefectureInfo prefecture-name="hiroshima"/>
      <PrefectureInfo prefecture-name="yamaguchi"/>
      <PrefectureInfo prefecture-name="tokushima"/>
      <PrefectureInfo prefecture-name="kagawa"/>
      <PrefectureInfo prefecture-name="ehime"/>
      <PrefectureInfo prefecture-name="kochi"/>
      <PrefectureInfo prefecture-name="fukuoka"/>
      <PrefectureInfo prefecture-name="saga"/>
      <PrefectureInfo prefecture-name="nagasaki"/>
      <PrefectureInfo prefecture-name="kumamoto"/>
      <PrefectureInfo prefecture-name="oita"/>
      <PrefectureInfo prefecture-name="miyazaki"/>
      <PrefectureInfo prefecture-name="kagoshima"/>
      <PrefectureInfo prefecture-name="okinawa"/>
  </v-app>
</template>

<script>
import Navbar from './components/Navbar.vue';
import EndpointsList from './components/EndpointsList.vue';
import PrefectureInfo from './components/PrefectureInfo.vue';
import EndpointInfo from './components/EndpointInfo.vue';

export default {
  name: 'App',

  components: {
    Navbar,
    EndpointsList,
    PrefectureInfo,
    EndpointInfo,
  },

  data: () => ({
  //
  }),
};
</script>

<style>
.v-breadcrumbs__item {
  color: #f18282 !important;
}
</style>
