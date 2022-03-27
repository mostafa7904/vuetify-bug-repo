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
          <v-chip color="primary" class="ml-2" small> # Tutorial </v-chip>
          <v-chip color="primary" small> # Blog </v-chip>
        </v-card-subtitle>
        <v-card-text class="text-right">
          <a
            class="text-decoration-none blog-post-title text--primary"
            href="https://example.com"
          >
            The link
          </a>
        </v-card-text>
      </v-card>
    </v-col>
  </v-row>
</template>

<script>
export default {
  name: 'IndexPage',
}
</script>
