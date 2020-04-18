<template>
  <v-col cols="12"
         class=""
         style="">
    <v-row justify="center"
           style="">
      <driver-application-form />
    </v-row>
  </v-col>
</template>


<script>
import DriverApplicationForm from '@/components/DriverApplicationForm'

export default {
  layout: 'heropage',
  components: {
    DriverApplicationForm
  }
}
</script>

<style>
</style>