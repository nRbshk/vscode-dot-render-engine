<script setup lang="ts">
import { RouterView } from "vue-router";
import "primevue/resources/primevue.min.css";
import "primevue/resources/themes/bootstrap4-dark-blue/theme.css";
// import "primevue/resources/themes/bootstrap4-light-blue/theme.css";
// import "primevue/resources/themes/mdc-light-indigo/theme.css";
// import "primevue/resources/themes/arya-blue/theme.css";
// import "primevue/resources/themes/fluent-light/theme.css";
// import "primevue/resources/themes/lara-dark-purple/theme.css";
// import "primevue/resources/themes/lara-dark-blue/theme.css";
// import "primevue/resources/themes/lara-light-blue/theme.css";
// import "primevue/resources/themes/luna-amber/theme.css";
// import "primevue/resources/themes/luna-green/theme.css";
// import "primevue/resources/themes/md-dark-deeppurple/theme.css";
// import "primevue/resources/themes/md-light-indigo/theme.css";
// import "primevue/resources/themes/mdc-dark-indigo/theme.css";
// import "primevue/resources/themes/nova/theme.css";
// import "primevue/resources/themes/nova-alt/theme.css";
// import "primevue/resources/themes/rhea/theme.css";
// import "primevue/resources/themes/saga-blue/theme.css";
// import "primevue/resources/themes/saga-orange/theme.css";
// import "primevue/resources/themes/tailwind-light/theme.css";
// import "primevue/resources/themes/vela-purple/theme.css";

import "primeicons/primeicons.css";
import "primeflex/primeflex.css";

import AppMenuBar from "./components/AppMenuBar.vue";
</script>

<template>
  <header>
    <AppMenuBar />
  </header>
  <RouterView />
</template>
