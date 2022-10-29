<template>
<main>
  <div>
    <NavBar />
  </div>

<!-- Site Content == Between the <div> tags -->
<div class="main-content">
</div>   
<section class="container">
    <div>
      <app-logo/>
      <h1 class="title">
        Engineers in Action
      </h1>
      <h2 class="subtitle">
        Rutgers University
      </h2>
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
      img-src="../assets/homePage1.jpg"
    ></b-carousel-slide>
    <b-carousel-slide
      caption="Capiana, Bolivia 2018"
      img-src="../assets/homePage2.jpg"
    ></b-carousel-slide>
  </b-carousel>
      <h3 class = "keyPoints">
        About Us
      </h3>
      <p class = description>
        Engineers In Action is an international non-proft organization whose goal is to connect vital resources to isolated communities in developing countries. These communities often have difficulties getting to infrastructure such as schools, hospitals or even work due impassable rivers during the rainy season. The EIA Rutgers University chapter was established in the Spring of 2016 to help fight the problem. In the summer we participated as a tag along with Colorado Boulder University to construct our first pedestrian footbridge in Churo Alto, Bolivia.
      </p>
      <p class = description>
        Engineers In Action strives to improve the conditions of isolated communities through the construction of pedestrian footbridges in these areas. Our EIA chapter collaborates alongside community members, university students and our in-country partner, Engineers in Action-Parent organization in order to accomplish this effort. EIA collaborates with local partners and communities to develop cost-effiecient alternatives for many bridge components. And this is the main reason we can still afford construction of footbridges in remote areas.
      </p>
    </div>
  </section>
    
<!-- Site footer -->
<div class="push"></div>
    <Footer />

</main>

</template>

<script>

  export default {
    name: 'IndexPage', 
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

.container {
  min-height: 100vh;
  padding-top: 0px;
  display: flex;
  justify-content: center;
  align-items: top;
  text-align: center;
}
.title {
  font-family: "Quicksand", "Source Sans Pro", -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, "Helvetica Neue", Arial, sans-serif; /* 1 */
  display: block;
  font-weight: 300;
  font-size: 100px;
  /*color: #35495e;*/
  letter-spacing: 1px;
}
.subtitle {
  font-weight: 300;
  font-size: 42px;
  /*color: #526488;*/
  word-spacing: 5px;
  padding-bottom: 15px;
}

.keyPoints {
  font-weight: 300;
  font-size: 42px;
  /*color: #526488;*/
  word-spacing: 5px;
  padding-bottom: 15px;
  padding-top: 50px;
}

.links {
  padding-top: 15px;
}

.description {
  font-weight: 100px;
  font-size: 24px;
  /*color: #526488;*/
  word-spacing: 5px;
  padding-bottom: 15px;
  padding-top: 15px;
  justify-content: center;
  align-items: top;
  text-align: left;
  text-indent: 50px;
}
</style>
