<template>
  <v-col cols="12"
         class="mt-4"
         style="">
    <v-row justify="center"
           class="">
      <div class="">
        <h1 class="display-4 font-weight-black">TREAD</h1>
      </div>
    </v-row>
    <v-row justify="center"
           class="">
      <h2 class="font-weight-bold">TRANSPORTATION</h2>
    </v-row>
    <v-row justify="center"
           class="px-8 py-6">
      <p class="font-weight-light pt-5">
        The first class FedEx delivery partner of the south. Lorem ipsum or sit
        amet, consectetur adipiscing elit, sed deserunt mollit anim id est
        laborum.
      </p>
    </v-row>
    <v-row justify="center">
      <svg width="59"
           height="4"
           viewBox="0 0 59 4"
           fill="none"
           xmlns="http://www.w3.org/2000/svg">
        <rect x="0.868011"
              y="0.0839844"
              width="57.265"
              height="3"
              fill="#A4D2FF" />
      </svg>
    </v-row>
    <v-row justify="center"
           class="pt-12">
      <v-btn color="#F06D87"
             rounded
             to="/faq"
             class="white--text">DRIVER BENEFITS</v-btn>
    </v-row>
    <v-row class="pt-8">
      <img width="100%"
           height="250px"
           src="~/static/mobile-graphic.svg" />
    </v-row>
  </v-col>
</template>

<script>
import Logo from '~/components/Logo.vue'
import HeroHeader from '~/components/HeroHeader.vue'
export default {
  layout: 'heropage',
  components: {
    Logo,
    HeroHeader
  }
}
</script>
<style lang="scss">
.hero-text {
  // position: absolute;
  // height: 93px;
  // left: -16.67%;
  // right: -17.33%;
  // top: calc(50% - 93px / 2 + 1.5px);

  font-style: normal;
  font-weight: bold;
  font-size: 39px;
  line-height: 45px;
  /* or 115% */

  text-align: center;
  color: #394d8b;
}
p {
  text-align: center;
}
.v-btn {
  box-shadow: none;
}
h2 {
  letter-spacing: 0.35rem;
}
</style>
