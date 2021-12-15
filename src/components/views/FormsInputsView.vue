<template>
  <v-row class="pa-6">
    <v-col md="12">
      <v-row no-gutters>
        <v-col md="6">
          <p>XXXX</p>
        </v-col>
        <v-col md="6">
          <p>XXXX</p>
        </v-col>
      </v-row>
    </v-col>
  </v-row>
</template>


<script>
export default {
  name: "App",

  data() {
    return {
      select: ["Vuetify", "Programming"],
      items: ["Programming", "Design", "Vue", "Vuetify"],
      alertType: "success",
    };
  },
};
</script>
 