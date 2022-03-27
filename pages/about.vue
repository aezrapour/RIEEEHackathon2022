<template>
    <main>
<div><NavBar /></div>
    

<b-container profile class="p-4 bg-light">
  <b-row>
    <b-col>
      <h2>Matthew Kolb</h2>
      <h3>President</h3>
      <b-img rounded="circle" id="Prez" thumbnail profile src="https://b2p.rutgers.edu/sites/all/themes/nexus/images/eboardpics/pres.jpg" alt="Image 1"
       width = "300"
       length = "300"
      >
      
      
      </b-img>
    </b-col>
    <b-col>
      <h2>Rishika Padnani</h2>
      <h3>Vice President</h3>
      <b-img rounded="circle" thumbnail profile src="https://b2p.rutgers.edu/sites/all/themes/nexus/images/eboardpics/vicepres.jpg" alt="Image 2"
       width = "300"
       length = "300"
      ></b-img>
    </b-col>
  </b-row>
</b-container>

  </main>

</template>

<script>
export default {
  name: 'AboutPage'
}
</script>

<style scoped>
div {
    text-align: center;
}

img {
  border: 10px solid rgb(0, 0, 0);
}

</style>