<script setup>
import { RouterView } from "vue-router";

import HeaderView from "@/components/HeaderView.vue";
import FooterView from "@/components/FooterView.vue";
</script>

<template>
  <HeaderView />
  <RouterView />
  <FooterView />

  <a
    href="https://api.whatsapp.com/send?phone=5493413030732&amp;text=Hola%21%20Quisiera%20m%C3%A1s%20informaci%C3%B3n."
    class="btn btn-secondary wa-float d-flex align-items-center justify-content-center"
    target="_blank"
  >
    <i class="bi bi-whatsapp my-wa-float"></i>
  </a>
</template>
