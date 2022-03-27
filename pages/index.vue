<template>
  <v-row>
    <v-col cols="12">
      <v-card
        link
        href="https://example.com"
        flat
        color="white"
        class="mx-auto"
        max-width="400"
        rounded="xl"
      >
        <v-img contain max-height="250" src="/test.avif"> </v-img>
        <v-card-subtitle class="text-right">
          V-card-subtitle content
        </v-card-subtitle>
        <v-card-text class="text-right">
          <!-- Comment this link or remove the href and link attrs from v-card and see all the duplicate contents disapear -->
          <a
            class="text-decoration-none text--primary"
            href="https://example.com"
          >
            The link in v-card-text
          </a>
        </v-card-text>
        <v-card-actions> V-card-actions contents </v-card-actions>
      </v-card>
    </v-col>
  </v-row>
</template>

<script>
export default {
  name: 'IndexPage',
}
</script>
