<script setup>
import Navbar from "../components/Navbar.vue";
import Layout from "../components/Layout.vue";
</script>

<template>
  <div class="nav-top-main">
    <Navbar />
    <Layout />
  </div>
  <div class="about">
    <p>This is an about page</p>
  </div>
</template>

<style>
.about {
  padding: 0;
  text-align: center;
}
.about p {
  font-family: "Courier New", Courier, monospace;
  font-weight: bold;
  font-size: 32px;
}
</style>
