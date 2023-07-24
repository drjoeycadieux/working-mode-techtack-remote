<script>
export default {
  data() {
    return {
      currentYear: new Date().getFullYear(),
    };
  },
};
</script>

<template>
  <div class="footer">
    <p>&copy; Techtack-Technologies 2020 - {{ currentYear }}</p>
  </div>
</template>

<style>
.footer {
  background-color: #32394e;
  padding: 25px;
}
.footer p {
  text-align: center;
  font-family: sans-serif;
  font-size: 23px;
  color: white;
}
</style>
