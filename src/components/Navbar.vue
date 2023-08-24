<script></script>

<template>
  <div class="navbar-menu">
    <ul>
      <img
        class="logo-nav"
        src="https://techtack-technologies.com/assets/logo_main.png"
      />
      <p class="title">Techtack Technologies &rarr; <span>Internal</span></p>
      <router-link class="linknav" to="/">Home</router-link>
      <router-link class="linknav" to="/about">About</router-link>
      <router-link class="linknav" to="/insiders/GlobalNetwork"
        >Global Network</router-link
      >
    </ul>
  </div>
</template>

<style>
.logo-nav {
  width: 95px;
  justify-content: center;
  border-radius: 10px;
}
.navbar-menu {
  padding: 15px;
  background-color: #32394e;
}
.title {
  display: inline;
  margin: 8px;
  font-family: sans-serif;
  font-weight: bold;
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
