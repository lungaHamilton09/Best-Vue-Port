<template>
  <nav></nav>

  <!-- home section  -->
  <div class="main-container">
    <div class="left-section"></div>
    <div class="right-section"></div>

    <div class="image-container">
      <img src="../images/IMG_1691.jpg" alt="#" class="hero-image">
    </div>

    <div class="home-left-container"> 

      <div class="home-inner-text">
        <h1 class="font-text-small">Hello, I'm </h1>
        <h1 class="font-text-large">Lunga Momoza </h1>
        <h1 class="font-text-small">Software Developer</h1>
      </div>

      <div class="home-button-container">
        <button class="Button">Download CV</button>
        <button class="Button">Contact Info</button>
      </div>

      <div class="home-links-container">
        <a href="">
          <img src="#" alt="mail" class="icon">
        </a>
        <a href="">
          <img src="#" alt="linkedin" class="icon">
        </a>
        <a href="">
          <img src="#" alt="github" class="icon">
        </a>
      </div>
    </div>
  </div>



  <!-- About section -->
  <div class="about-container">

  </div>

  <!-- experience section -->
  <div class="experience-container">

  </div>

  <!-- projects section -->
  <div class="projects-container">

  </div>

  <!-- contact section -->
  <div class="contact-container">

  </div>

 
</template>

<script>
export default {
  name: 'HomeCard'
}
</script>

<style scoped>

/* home section  */
.main-container {
  display: flex;
  flex-direction: row;
  width: 100%;
  height: 100vh;
  /* height: 100%; */
  /*make my container split horizontally with these 2 colors */
   background-color: #664229;
  background-color: #FFF5E2;

}
.image-container {
  display: flex;
  flex-direction: column;
  justify-content: center;
  align-items: center;
  width: 40vw;
  height: 100%;
}
.hero-image {
  width: 60%;
  height: 60%;
  border-radius: 50%;
}
.home-left-container {
  display: flex;
  flex-direction: column;
  justify-content: center;
  align-items: center;
  width: 60vw;
  height: 100%;
  background-color: rgb(131, 66, 66);
}
.home-inner-text {
  display: flex;
  flex-direction: column;
  justify-content: center;
  align-items: center;
  /* gap: 1rem; */
}
.home-button-container {

}
.home-links-container {

}
.home-links-container a {
  text-decoration: none;
  color: white;
}

/* about section */


/* font styles */
.font-text-small {
  font-family: Arial, Helvetica, sans-serif;
  font-size: 1rem;
  line-height: 1;
}
.font-text-large {
  font-family: Arial, Helvetica, sans-serif;
  font-size: 3rem;
  line-height: 1;
}
.font-text-small {
  font-family: Arial, Helvetica, sans-serif;
  font-size: 2rem;
  line-height: 1;
}
</style>
  