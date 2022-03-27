<template>
<main>
  <div>
    <NavBar />
    </div>
<div class="cal-wrapper">
  <b-calendar today-variant="info" selected-variant="success" block locale="en-US" nav-button-variant="primary"></b-calendar>
</div>
<div class="push">
  <Footer />
  </div>

</main>
</template>

<script>
export default {
  name: 'EventsPage'
}
</script>
<style>
.push {
  height: 50px;
}
.cal-wrapper{
  background-color: white;;
}
</style>