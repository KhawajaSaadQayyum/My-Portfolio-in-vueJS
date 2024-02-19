

<script setup>
defineProps({
  msg: {
    type: String,
    required: true
  }
})
</script>

<template>
 <!-- Container (About Section) -->
<div class="w3-content w3-container w3-padding-64" id="about">
  <h3 class="w3-center">ABOUT ME</h3>
  <p class="w3-center"><em>I love Web development</em></p>
  <p>As a Full-stack Developer with over a year of professional experience, I have created efficient and reliable software solutions. My expertise lies in Vue JS, Spring boot, and object-oriented design. I have successfully contributed as a full-stack developer for the development of multiple web applications in my previous company, I am Committed to delivering high-quality solutions that meet client requirements and enhance user experience. If you are seeking a motivated and dedicated full-stack Developer with a strong foundation and a passion for excellence, I am excited to explore new opportunities where I can contribute to the success of your team and organization.</p>
  <div class="w3-row">
    <div class="w3-col m6 w3-center w3-padding-large">
      <p><b><i class="fa fa-user w3-margin-right"></i>Saad Qayyum</b></p><br>
      <img src="/images/avatar_hat.jpg" class="w3-round w3-image w3-opacity w3-hover-opacity-off" alt="Photo of Me" width="500" height="333">
    </div>

    <!-- Hide this text on small devices -->
    <div class="w3-col m6 w3-hide-small w3-padding-large">
      <p>As a Full-stack Developer with one year of professional experience, I have created efficient and reliable software solutions for telecom giants like Jazz Pakistan, Saudi STC, and Qatar Vodafone.</p>
      <p>Leveraging Vue.js for front-end and Spring Boot for back-end, I translated business requirements into innovative technical solutions, ensuring seamless integration and optimal performance.</p>
      <p>I collaborated cross-functionally, conducted rigorous testing, and contributed to ongoing process enhancements, maintaining a focus on delivering high-quality, client-centric solutions.</p>
    </div>
  </div>
  <p class="w3-large w3-center w3-padding-16">Im really good at:</p>
  <p class="w3-wide"><i class="fa fa-code"></i>Web development</p>
  <div class="w3-light-grey">
    <div class="w3-container w3-padding-small w3-dark-grey w3-center" style="width:90%">90%</div>
  </div>
  <p class="w3-wide"><i class="fa fa-laptop"></i>Web Design</p>
  <div class="w3-light-grey">
    <div class="w3-container w3-padding-small w3-dark-grey w3-center" style="width:85%">85%</div>
  </div>
  <p class="w3-wide"><i class="fa fa-mobile"></i>App development</p>
  <div class="w3-light-grey">
    <div class="w3-container w3-padding-small w3-dark-grey w3-center" style="width:85%">85%</div>
  </div>
</div>

<div class="w3-row w3-center w3-dark-grey w3-padding-16">
  <div class="w3-quarter w3-section">
    <span class="w3-xlarge">4+</span><br>
    Partners
  </div>
  <div class="w3-quarter w3-section">
    <span class="w3-xlarge">5+</span><br>
    Projects Done
  </div>
  <div class="w3-quarter w3-section">
    <span class="w3-xlarge">9+</span><br>
    Happy Clients
  </div>
  <div class="w3-quarter w3-section">
    <span class="w3-xlarge">20+</span><br>
    Meetings
  </div>
</div>
</template>

<style scoped>

</style>