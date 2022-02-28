<template>
  <v-container>
    <v-row>
      <v-col v-for="(terminal, idx) of terminals" :key="idx">
        <v-card @click="$router.push(terminal.path)" max-width="300">
          <v-card-title>{{terminal.label}}</v-card-title>
        </v-card>
      </v-col>
    </v-row>
  </v-container>
</template>

<script>
export default {
  name: "HomeView",
  data() {
    return {
      terminals: [
        {label: "Szklenie", path: "/glazing"},
         {label: "Poszerzenia", path: "/extensions"}
      ]
    };
  },
};
</script>
