<template>
  <v-col cols="12"
         class="pa-0 mt-4"
         style="">
    <v-row justify="center"
           style="">

      <!-- <img src="/v.png"
           alt="Vuetify.js"
           class="mb-5"> -->
      <vuetify-logo />
      <blockquote class="blockquote">
        &#8220;First, solve the problem. Then, write the code.&#8221;
        <footer>
          <small>
            <em>&mdash;John Johnson</em>
          </small>
        </footer>
      </blockquote>

    </v-row>
  </v-col>
</template>


<script>
import VuetifyLogo from '@/components/VuetifyLogo'

export default {
  layout: 'heropage',
  components: {
    VuetifyLogo
  }
}
</script>

<style>
</style>