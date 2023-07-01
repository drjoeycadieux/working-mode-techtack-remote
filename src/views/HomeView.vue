<script setup>
import Navbar from "@/components/Navbar.vue";
</script>

<template>
  <main>
    <Navbar />
    <div class="homeView">
      <p>HomeView</p>
    </div>
  </main>
</template>

<style>
.homeView {
  padding: 5px;
  padding-top: 100px;
}

.homeView p {
  text-align: center;
  font-family: sans-serif;
  color: black;
  font-weight: bold;
  font-size: 25px;
}
</style>
