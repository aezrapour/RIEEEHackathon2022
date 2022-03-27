<template>
<main>
    <NavBar />

    <!-- Site Content == Between the <div> tags -->
<div>
  <h2 class = "subtitle"> Capiana, Bolivia 2018 </h2>
  <b-carousel
    id="carousel-fade"
    style="text-shadow: 0px 0px 2px #000"
    fade
    indicators
    img-width="800"
    img-height="400"
  >
    <b-carousel-slide
      caption=""
      img-src="https://b2p.rutgers.edu/sites/default/files/gallery/photos%20/IMAG5372.jpg"
    ></b-carousel-slide>
    <b-carousel-slide
      caption=""
      img-src="https://b2p.rutgers.edu/sites/default/files/gallery/photos%20/%2846%29.jpg"
    ></b-carousel-slide>
    <b-carousel-slide
      caption=""
      img-src="https://b2p.rutgers.edu/sites/default/files/gallery/photos%20/%2862%29.jpg"
    ></b-carousel-slide>
  </b-carousel>

    <h2 class = 'subtitle'>Palmar Pampa B, Bolvia 2017</h2>
    <b-carousel
    id="carousel-fade"
    style="text-shadow: 0px 0px 2px #000"
    fade
    indicators
    img-width="1024"
    img-height="480"
  >
    <b-carousel-slide
      caption="Palmar Pampa B, Bolivia 2017"
      img-src="https://b2p.rutgers.edu/sites/default/files/gallery/photos%20/20170713_145524.jpg"
    ></b-carousel-slide>
    <b-carousel-slide
      caption=""
      img-src="https://b2p.rutgers.edu/sites/default/files/gallery/photos%20/20170818_084949.jpg"
    ></b-carousel-slide>
    <b-carousel-slide
      caption=""
      img-src="https://b2p.rutgers.edu/sites/default/files/gallery/photos%20/20170819_100321.jpg"
    ></b-carousel-slide>
  </b-carousel>

</div>


    <!-- Site footer -->
<div class="push"></div>
    <Footer />
</main>
</template>

<script>

  export default {
    name: 'GalleryPage', 
    data() {
      return {
        slide: 0,
        sliding: null
      }
    },
    methods: {
      onSlideStart(slide) {
        this.sliding = true
      },
      onSlideEnd(slide) {
        this.sliding = false
      }
    }
  }

</script>
<style scoped>
.push {
  height: 50px;
}

.subtitle {
  padding-top: 35px;
  padding-bottom: 20px;
  text-align: center;
}
</style>