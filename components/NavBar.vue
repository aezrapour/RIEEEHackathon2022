<template>
<div>
  <b-navbar toggleable="lg" type="dark" variant="info">
    <b-navbar-brand href="/"><b-img src="../eia-logo.png" fluid alt="Responsive image"></b-img></b-navbar-brand>

    <b-navbar-toggle target="nav-collapse"></b-navbar-toggle>

    <b-collapse id="nav-collapse" is-nav>
      <b-navbar-nav>
        <b-nav-item href="/">Home</b-nav-item>
        <b-nav-item href="/about">E-board</b-nav-item>
        <b-nav-item href="/gallery">Gallery</b-nav-item>
        <b-nav-item href="/event">Events</b-nav-item>
        <b-nav-item href="/donate">Donate</b-nav-item>
      </b-navbar-nav>

      <!-- Right aligned nav items -->
      <b-navbar-nav class="ml-auto">
        <b-nav-text>Follow Us:</b-nav-text>
<b-nav-item href="https://www.facebook.com/eia.rutgers"><b-icon icon="facebook" aria-hidden="true"></b-icon></b-nav-item>

        <b-nav-item href="https://www.instagram.com/ru_eia"><b-icon icon="instagram" aria-hidden="true"></b-icon></b-nav-item>

      </b-navbar-nav>
    </b-collapse>
  </b-navbar>
</div>
</template>