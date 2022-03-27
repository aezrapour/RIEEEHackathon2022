<template>
<header>
<div>
  <b-navbar toggleable="lg">
    <b-navbar-brand href="/"><b-img src="../eia-logo.png" fluid alt="Responsive image"></b-img></b-navbar-brand>

    <b-navbar-toggle target="nav-collapse"></b-navbar-toggle>

    <b-collapse id="nav-collapse" is-nav>
      <b-navbar-nav>
        <b-nav-item href="/">Home</b-nav-item>
        <b-nav-item href="/about">E-board</b-nav-item>
        <b-nav-item href="/gallery">Gallery</b-nav-item>
        <b-nav-item href="/events">Events</b-nav-item>
        <b-nav-item href="/Contribute">Contribute</b-nav-item>
      </b-navbar-nav>

      <!-- Right aligned nav items -->
      <b-navbar-nav class="ml-auto">
        <b-nav-text bold >Follow us:</b-nav-text>
<b-nav-item target="_blank" href="https://www.facebook.com/eia.rutgers"><b-icon icon="facebook" aria-hidden="true"></b-icon></b-nav-item>

        <b-nav-item target="_blank" href="https://www.instagram.com/ru_eia"><b-icon icon="instagram" aria-hidden="true"></b-icon></b-nav-item>

      </b-navbar-nav>
    </b-collapse>
  </b-navbar>
</div>
<div class="push"></div>
</header>
</template>
<style scoped>
.push{
  height: 5px;
  background-color: red;
  margin-bottom: 10px;
}
</style>
