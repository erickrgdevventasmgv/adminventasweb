<script setup lang="ts">
//import { RouterLink } from "vue-router";
import FirstView from "@/components/FirstView.vue";
</script>

<template>
  <header>
    <img
      alt="Vue logo"
      class="logo"
      src="@/assets/logo.svg"
      width="125"
      height="125"
    />

    <div class="wrapper">
      <FirstView></FirstView>

      <nav></nav>
    </div>
  </header>
</template>
