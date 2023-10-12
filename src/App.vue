<script setup lang="ts">
import InputArea from "@/components/InputArea.vue";
import Header from "@/components/Header.vue";
import Footer from "@/components/Footer.vue";
</script>

<template>
  <Header />
  <main>
    <InputArea/>
  </main>
  <Footer />
</template>

<style scoped>

main {
  background-color: black;
  flex-grow: 1;
}
</style>
