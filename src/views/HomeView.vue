<script setup>
import InfoBanner from "../components/InfoBanner.vue";
import Header from "../components/Header.vue";
import Navbar from "../components/Navbar.vue";
</script>

<template>
  <main>
    <Navbar />
    <Header />
    <InfoBanner />
    <div class="homeView">
      <p>HomeView</p>
    </div>
  </main>
</template>

<style>
.homeView {
  padding: 5px;
  margin-top: 100px;
}
.homeView p {
  text-align: center;
  font-family: sans-serif;
  color: black;
  font-weight: bold;
  font-size: 25px;
}
</style>
