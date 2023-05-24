<template>
  <div class="navbar">
    <img src="@/assets/vue.svg" alt="" />
    <div class="navbar-menu">
      <PhTimer :size="32" class="navbar-icon-active"></PhTimer>
      <PhPaperPlane :size="32"></PhPaperPlane>
    </div>
  </div>
</template>

<script setup>
import { PhPaperPlane, PhTimer } from "@phosphor-icons/vue";
</script>

<style scoped lang="scss">
@import "@/scss/modules/Navbar.module.scss";
</style>