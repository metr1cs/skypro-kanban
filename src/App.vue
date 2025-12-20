<script setup>
import BaseButton from "@/components/BaseButton.vue";
import HomeView from "@/components/HomeView.vue";
import BaseHeader from "@/components/BaseHeader.vue";
import NewCardModal from "@/components/NewCardModal.vue";
import ExitModal from "@/components/ExitModal.vue";
</script>

<template>

  <main>
    <base-header/>
    <home-view/>
    <new-card-modal/>
    <exit-modal/>
    <base-button/>
  </main>
</template>

<style scoped>
</style>
