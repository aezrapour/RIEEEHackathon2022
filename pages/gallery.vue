<template>
    <main>
    <h1>Gallery page</h1>
        <NuxtLink to="/">
      Home
    </NuxtLink>
    <NuxtLink to="/about">
      About
    </NuxtLink>
        <NuxtLink to="/event">
      Events
    </NuxtLink>
        <NuxtLink to="/donate">
      Donate
    </NuxtLink>
        <NuxtLink to="/gallery">
      Gallery
    </NuxtLink>
  </main>
</template>

<script>
export default {
  name: 'GalleryPage'
}
</script>