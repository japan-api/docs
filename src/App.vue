<template>
  <v-app>
    <v-content>
      <Navbar/>
      <Logo/>
      <PrefectureInfo prefecture-name="tokyo"/>
      <PrefectureInfo prefecture-name="osaka"/>
      <PrefectureInfo prefecture-name="kyoto"/>
      <PrefectureInfo prefecture-name="okinawa"/>
      <PrefectureInfo prefecture-name="hokkaido"/>
    </v-content>
  </v-app>
</template>

<script>
import Navbar from './components/Navbar.vue';
import Logo from './components/Logo.vue';
import PrefectureInfo from './components/PrefectureInfo.vue';

export default {
  name: 'App',

  components: {
    Navbar,
    Logo,
    PrefectureInfo,
  },

  data: () => ({
  //
  }),
};
</script>
