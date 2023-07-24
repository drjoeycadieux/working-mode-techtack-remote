<script setup>
import InfoBanner from "../components/InfoBanner.vue";
import Header from "../components/Header.vue";
import Navbar from "../components/Navbar.vue";
import Layout from "../components/Layout.vue";
import Footer from "../components/Footer.vue";
</script>

<template>
  <main>
    <Navbar />
    <Layout />
    <Header />
    <InfoBanner />
    <div class="homeView">
      <center>
        <img src="../assets/techtack-technologies.png" />
      </center>
    </div>
    <Footer />
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
