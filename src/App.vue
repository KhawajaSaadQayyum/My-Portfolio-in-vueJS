<script setup>
import Home from './components/Home.vue'
import About from './components/About.vue'
import Portfolio from './components/Portfolio.vue'
import Contact from './components/Contact.vue'
// Change style of navbar on scroll
window.onscroll = function() {myFunction()};
function myFunction() {
    var navbar = document.getElementById("myNavbar");
    if (document.body.scrollTop > 100 || document.documentElement.scrollTop > 100) {
        navbar.className = "w3-bar" + " w3-card" + " w3-animate-top" + " w3-white";
    } else {
        navbar.className = navbar.className.replace(" w3-card w3-animate-top w3-white", "");
    }
}

// Used to toggle the menu on small screens when clicking on the menu button
function toggleFunction() {
    var x = document.getElementById("navDemo");
    if (x.className.indexOf("w3-show") == -1) {
        x.className += " w3-show";
    } else {
        x.className = x.className.replace(" w3-show", "");
    }
}

</script>

<template>
  <header>
<div class="navbar">
  <!-- Navbar (sit on top) -->
<div class="w3-top">
  <div class="w3-bar" id="myNavbar">
    <a class="w3-bar-item w3-button w3-hover-black w3-hide-medium w3-hide-large w3-right" href="javascript:void(0);" onclick="toggleFunction()" title="Toggle Navigation Menu">
      <i class="fa fa-bars"></i>
    </a>
    <a href="#home" class="w3-bar-item w3-button">HOME</a>
    <a href="#about" class="w3-bar-item w3-button w3-hide-small"><i class="fa fa-user"></i> ABOUT</a>
    <a href="#portfolio" class="w3-bar-item w3-button w3-hide-small"><i class="fa fa-th"></i> PORTFOLIO</a>
    <a href="#contact" class="w3-bar-item w3-button w3-hide-small"><i class="fa fa-envelope"></i> CONTACT</a>
    <a href="#" class="w3-bar-item w3-button w3-hide-small w3-right w3-hover-red">
      <i class="fa fa-search"></i>
    </a>
  </div>

  <!-- Navbar on small screens -->
  <div id="navDemo" class="w3-bar-block w3-white w3-hide w3-hide-large w3-hide-medium">
    <a href="#about" class="w3-bar-item w3-button" onclick="toggleFunction()">ABOUT</a>
    <a href="#portfolio" class="w3-bar-item w3-button" onclick="toggleFunction()">PORTFOLIO</a>
    <a href="#contact" class="w3-bar-item w3-button" onclick="toggleFunction()">CONTACT</a>
    <a href="#" class="w3-bar-item w3-button">SEARCH</a>
  </div>
</div>

<!-- First Parallax Image with Logo Text -->
<!-- <div class="bgimg-1 w3-display-container w3-opacity-min" id="home">
  <div class="w3-display-middle" style="white-space:nowrap;">
    <span class="w3-center w3-padding-large w3-black w3-xlarge w3-wide w3-animate-opacity">MY <span class="w3-hide-small">WEBSITE</span> LOGO</span>
  </div>
</div> -->
<!-- Second Parallax Image with Portfolio Text -->
<div class="bgimg-2 w3-display-container w3-opacity-min">
  <div class="w3-display-middle">
    <span class="w3-xxlarge w3-text-white w3-wide">PORTFOLIO</span>
  </div>
</div>
</div>

    <div class="Home">
      <Home/>
    </div>
    <div class="About">
      <About/>
    </div>
    <div class="Portfolio">
      <Portfolio/>
    </div>
    <div class="contact">
      <Contact/>
    </div>
  </header>
  <!-- Footer -->
<footer class="w3-center w3-black w3-padding-64 w3-opacity w3-hover-opacity-off">
  <a href="#home" class="w3-button w3-light-grey"><i class="fa fa-arrow-up w3-margin-right"></i>To the top</a>
  <div class="w3-xlarge w3-section">
    <a href="https://www.facebook.com/khawaja.saad.391#" title="khawaja" target="_blank" class="w3-hover-text-green"><i class="fa fa-facebook-official w3-hover-opacity"></i></a>
    <a href="https://www.instagram.com/khawaja_saad_0?igsh=ZTJnMWl3MWsyN3Aw&utm_source=qr" title="khawaja" target="_blank" class="w3-hover-text-green"> <i class="fa fa-instagram w3-hover-opacity"></i></a>
    <a href="https://x.com/saadqay29307413?s=11" title="khawaja" target="_blank" class="w3-hover-text-green"><i class="fa fa-twitter w3-hover-opacity"></i></a> 
    <a href="https://www.linkedin.com/in/saad-qayyum4110" title="khawaja" target="_blank"><i>LinkedIn</i></a> 
  </div>
  <p>Powered by <a href="https://www.linkedin.com/in/saad-qayyum4110" title="khawaja" target="_blank" class="w3-hover-text-green">khawaja Saad Qayyum</a></p>
</footer>

  
</template>

<style scoped>

</style>
