<template>
  <v-container fluid>
    <v-tabs align-with-title v-model="tab">
      <v-tab key="tabRonan">Ronan</v-tab>
      <v-tab key="tabSovanda">Sovanda</v-tab>
      <v-tab key="tab3">Rady</v-tab>
    </v-tabs>

    <v-tabs-items v-model="tab">
      <v-tab-item key="tabRonan">
        <v-container fluid>
          <p class=".text-body-1">Something in tab Ronan</p>
        </v-container>
      </v-tab-item>

      <v-tab-item key="tabSovanda">
        <v-container fluid>
          <p class=".text-body-1">Something in tab Sovanda</p>
        </v-container>
      </v-tab-item>

      <v-tab-item key="tab3">
        <v-container fluid>
          <p class=".text-body-1">Something in tab 3</p>
        </v-container>
      </v-tab-item>
    </v-tabs-items>
  </v-container>
</template>

<script>
export default {
  name: "App",

  data() {
    return {
      tab: null,
    };
  },
};
</script>