<template>
    <main>
<header><NavBar /></header>
    
<div class="row">
  <div class="column">
    <div class="card">
      <img src="https://b2p.rutgers.edu/sites/all/themes/nexus/images/eboardpics/pres.jpg" alt="Jane" style="width:100%">
      <div class="container">
        <h2>Jane Doe</h2>
        <p class="title">CEO &amp; Founder</p>
        <p>Some text that describes me lorem ipsum ipsum lorem.</p>
      </div>
    </div>
  </div>

  <div class="column">
    <div class="card">
      <img src="https://b2p.rutgers.edu/sites/all/themes/nexus/images/eboardpics/vicepres.jpg" alt="Mike" style="width:100%">
      <div class="container">
        <h2>Mike Ross</h2>
        <p class="title">Art Director</p>
        <p>Some text that describes me lorem ipsum ipsum lorem.</p>
      </div>
    </div>
  </div>

  <div class="column">
    <div class="card">
      <img src="https://b2p.rutgers.edu/sites/all/themes/nexus/images/eboardpics/projectlead.jpg" alt="John" style="width:100%">
      <div class="container">
        <h2>John Doe</h2>
        <p class="title">Designer</p>
        <p>Some text that describes me lorem ipsum ipsum lorem.</p>
      </div>
    </div>
  </div>
</div>

<div class="row">
  <div class="column">
    <div class="card">
      <img src="	https://b2p.rutgers.edu/sites/all/themes/nexus/images/eboardpics/secretary.png" alt="Jane" style="width:100%">
      <div class="container">
        <h2>Jane Doe</h2>
        <p class="title">CEO &amp; Founder</p>
        <p>Some text that describes me lorem ipsum ipsum lorem.</p>
      </div>
    </div>
  </div>

 <div class="column">
    <div class="card">
      <img src="../jane.png" 
      alt="John" style="width:100%">
      <div class="container">
        <h2>John Doe</h2>
        <p class="title">Designer</p>
        <p>Some text that describes me lorem ipsum ipsum lorem.</p>
      </div>
    </div>
  </div>

  <div class="column">
    <div class="card">
      <img src="https://b2p.rutgers.edu/sites/all/themes/nexus/images/eboardpics/socialmedia.jpg" alt="John" style="width:100%">
      <div class="container">
        <h2>John Doe</h2>
        <p class="title">Designer</p>
        <p>Some text that describes me lorem ipsum ipsum lorem.</p>
      </div>
    </div>
  </div>
</div>
<div class="row">
  <div class="column">
    <div class="card">
      <img src="https://b2p.rutgers.edu/sites/all/themes/nexus/images/eboardpics/treasurer.jpg" alt="Jane" style="width:100%">
      <div class="container">
        <h2>Jane Doe</h2>
        <p class="title">CEO &amp; Founder</p>
        <p>Some text that describes me lorem ipsum ipsum lorem.</p>
      </div>
    </div>
  </div>

  <div class="column">
    <div class="card">
      <img src="https://b2p.rutgers.edu/sites/all/themes/nexus/images/eboardpics/events.jpg" alt="Mike" style="width:100%">
      <div class="container">
        <h2>Mike Ross</h2>
        <p class="title">Art Director</p>
        <p>Some text that describes me lorem ipsum ipsum lorem.</p>
      </div>
    </div>
  </div>

  <div class="column">
    <div class="card">
      <img src="https://b2p.rutgers.edu/sites/all/themes/nexus/images/eboardpics/webmaster.jpg" alt="John" style="width:100%">
      <div class="container">
        <h2>John Doe</h2>
        <p class="title">Designer</p>
        <p>Some text that describes me lorem ipsum ipsum lorem.</p>
      </div>
    </div>
  </div>
</div>

<div class="row">
  <div class="column">
    <div class="card">
      <img src="https://b2p.rutgers.edu/sites/all/themes/nexus/images/eboardpics/egcrep.png" alt="Jane" style="width:100%">
      <div class="container">
        <h2>Jane Doe</h2>
        <p class="title">CEO &amp; Founder</p>
        <p>Some text that describes me lorem ipsum ipsum lorem.</p>
      </div>
    </div>
  </div>
</div>

<div class="push"></div>
<Footer />
  </main>

</template>

<script>
export default {
  name: 'AboutPage'
}
</script>
<style scoped>
.push{
  height: 50px;
}

/* Three columns side by side */
.column {
  float: left;
  width: 50%;
  margin-bottom: 20px;
  padding: 0 16px;
  margin-left: auto;
  margin-right: auto;
  width: 22em
}


/* Display the columns below each other instead of side by side on small screens */
@media screen and (max-width: 650px) {
  .column {
    width: 100%;
    display: block;
  }
}

/* Add some shadows to create a card effect */
.card {
  box-shadow: 0 4px 8px 0 rgba(0, 0, 0, 0.2);
}

/* Some left and right padding inside the container */
.container {
  padding: 0 20px;
}

/* Clear floats */
.container::after, .row::after {
  content: "";
  clear: both;
  display: table;
}

.title {
  color: grey;
}

.button {
  border: none;
  outline: 0;
  display: inline-block;
  padding: 8px;
  color: white;
  background-color: #000;
  text-align: center;
  cursor: pointer;
  width: 100%;
}

.button:hover {
  background-color: #555;
}

</style>