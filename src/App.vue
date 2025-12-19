<script setup>
import BaseButton from "@/components/BaseButton.vue";
import HomeView from "@/components/view/HomeView.vue";
import BaseHeader from "@/components/view/BaseHeader.vue";
import NewCardModal from "@/components/view/NewCardModal.vue";
import ExitModal from "@/components/view/ExitModal.vue";
</script>

<template>

  <main>
    <base-header/>
    <home-view/>
    <new-card-modal/>
    <exit-modal/>
  </main>
</template>

<style scoped>
</style>
