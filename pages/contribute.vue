<template>
<main>
    <NavBar />


    <!-- Site Content == Between the <div> tags -->
<div class="main-content">
<p>Hello World</p>
<p>How is the World?</p>
</div>


    <!-- Site footer -->
<div class="push"></div>
    <Footer />
</main>
</template>

<script>
export default {
  name: 'DonatePage'
}
</script>
<style scoped>
.push {
  height: 50px;
}
</style>