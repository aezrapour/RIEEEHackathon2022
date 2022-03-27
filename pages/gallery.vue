<template>
<main>
    <NavBar />

    <!-- Site Content == Between the <div> tags -->
<div>
  <b-carousel
    id="carousel-fade"
    style="text-shadow: 0px 0px 2px #000"
    fade
    indicators
    img-width="1024"
    img-height="480"
  >
    <b-carousel-slide
      caption="First slide"
      img-src="https://picsum.photos/1024/480/?image=10"
    ></b-carousel-slide>
    <b-carousel-slide
      caption="Nulla vitae elit libero, a pharetra augue mollis interdum."
      img-src="https://picsum.photos/1024/480/?image=52"
    ></b-carousel-slide>
    <b-carousel-slide
      caption="Third Slide"
      img-src="https://picsum.photos/1024/480/?image=54"
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
</style>