<template>
  <v-container fluid>
    <v-row>
      <v-col cols="6">
        <v-chip small color="primary"> Fujinet AI Service </v-chip>
        <v-btn rounded text x-small>
          <v-icon x-small left color="primary">mdi-home</v-icon> Fujinet AI
          Service AAAAAAAAAAAA
        </v-btn>
        <v-icon dense>mdi-check-circle-outline</v-icon>
        <v-text-field flat outlined dense rounded placeholder="Search">
          <template #prepend-inner>
            <v-icon dense left>mdi-magnify</v-icon>
          </template>
        </v-text-field>
        <v-text-field flat outlined rounded placeholder="Search">
          <template #prepend-inner>
            <v-icon left>mdi-magnify</v-icon>
          </template>
        </v-text-field>
      </v-col>
    </v-row>
  </v-container>
</template>
<script>
export default {
  methods: {
    mouseHover() {
      console.log("mouseHover");
    },
  },
};
</script>
