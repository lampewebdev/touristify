<template>
  <v-app id="inspire">
    <v-content>
      <v-container
        class="fill-height"
        fluid
      >
        <v-row
          align="center"
          justify="center"
          style="max-width: initial"
        >
          <v-col
            cols="12"
            sm="8"
            md="6"
          >
            <nuxt />
          </v-col>
        </v-row>
      </v-container>
    </v-content>
  </v-app>
</template>

<script>
export default {
  props: {
    source: {
      type: String,
      default: null
    }
  }
}
</script>
