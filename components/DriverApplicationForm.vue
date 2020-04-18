<template>
  <v-container>
    <v-col cols="12">
      <v-row justify="start">
        <div class="">
          <h3 class="display-1">Driver Application</h3>
        </div>
        <p class="body-1 pt-3">Lorem ipsum dolor sit amet consectetur
          adipisicing
          elit. Distinctio,
          voluptas voluptates.</p>
      </v-row>
      <v-row class="mt-6">
        <v-col cols="12">
          <form v-on:submit.prevent="onContinue"
                method="POST">
            <v-text-field label="First Name" />
            <v-text-field label="Last Name" />
            <v-text-field label="Email" />
            <v-text-field label="Phone" />
            <v-btn type="submit">Continue</v-btn>
          </form>

        </v-col>
      </v-row>
    </v-col>
  </v-container>
</template>

<script>
export default {
  methods: {
    onContinue() {
      console.log('continue')
    }
  }
}
</script>

<style lang="scss" scoped>
p {
  text-align: left !important;
}
</style>