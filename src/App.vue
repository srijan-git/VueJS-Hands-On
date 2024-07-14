<script setup>
import Navbar from '@/components/Navbar.vue'
import { RouterView } from 'vue-router'
</script>
<template>
  <Navbar />
  <!-- <Hero title="Test title" subTitle="Test" />  //Props-->

  <RouterView />
</template>
