<template>
  <v-card>
      <v-card-title>{{poste}}</v-card-title>
      <v-card-subtitle style="text-align: left">Terminal Produkcyjny</v-card-subtitle>
  </v-card>
</template>
<script>
export default {
  props: { poste: { type: String, required: true } },
  data() {
    return {};
  },
};
</script>