<script setup>
import Navbar from "../../components/Navbar.vue";
</script>

<template>
  <div class="global">
    <Navbar />
    <div class="global-content">
      <p>Global Network Page</p>
    </div>
  </div>
</template>

<style>
.global-content {
  text-align: center;
  padding-top: 100px;
}

.global-content p {
  font-family: sans-serif;
  color: black;
  font-size: 25px;
}
</style>
