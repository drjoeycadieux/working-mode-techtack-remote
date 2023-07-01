<script></script>

<template>
  <div class="navbar-menu">
    <ul>
      <p class="title">Techtack Technologies (remote)</p>
      <router-link class="linknav" to="/">Home</router-link>
      <router-link class="linknav" to="/insiders/GlobalNetwork"
        >Global Network</router-link
      >
    </ul>
  </div>
</template>

<style>
.navbar-menu {
  padding: 25px;
  background-color: rgb(20, 26, 80);
}
.title {
  display: inline;
  margin: 8px;
  font-family: sans-serif;
  color: white;
  font-size: 26px;
}
.navbar-menu ul {
  display: block;
}
.linknav {
  color: white;
  text-decoration: none;
  font-family: sans-serif;
  margin: 8px;
}
.linknav:hover {
  color: lightslategray;
}
</style>
