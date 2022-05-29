<script setup lang="ts">
import Menubar from "primevue/menubar";

const menuItems = [
  {
    label: "Home",
    icon: "pi pi-fw pi-box",
    to: "/",
  },
];
</script>

<template>
  <Menubar class="menubar" :model="menuItems">
    <template #item="{ item }">
      <a role="menuitem">
        <span class="text-2xl" :class="item.icon"></span>
      </a>
    </template>
  </Menubar>
</template>
