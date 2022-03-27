<template>
<main>
  <div>
    <NavBar />
    </div>

    <div>
  <div>
  </div>
  <div class="mt-4">
    <h4>Upcoming Events:</h4>
    <b-card img-src="https://placekitten.com/300/300" img-alt="Card image" img-left class="mb-3">
      <b-card-text>
        Some quick example text to build on the card and make up the bulk of the card's content.
      </b-card-text>
    </b-card>
<div class="push"></div>
    <b-card img-src="https://placekitten.com/300/300" img-alt="Card image" img-right>
      <b-card-text>
        Some quick example text to build on the card and make up the bulk of the card's content.
      </b-card-text>
    </b-card>
  </div>
</div>
<div class="push"></div>
<div class="cal-wrapper">
  <b-calendar today-variant="info" selected-variant="success" block locale="en-US" nav-button-variant="primary"></b-calendar>
</div>

<div class="push"></div>
  <Footer />

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