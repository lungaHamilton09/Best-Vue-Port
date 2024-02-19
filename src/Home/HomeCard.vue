<template>
  <nav id="desktop-nav">
    <div class="logo">Lunga Momoza</div>
    <div>
      <ul class="nav-links">
        <li><a href="#about">About</a></li>
        <li><a href="#experience">Experience</a></li>
        <li><a href="#projects">Projects</a></li>
        <li><a href="#contact">Contact</a></li>
      </ul>
    </div>
  </nav>

  
<!-- home section  -->
  <div class="main-container">
    <div class="wallpaper"></div>




    <div class="image-container">
      <img src="../images/IMG_1691.jpg" alt="#" class="hero-image">
    </div>

    <div class="home-left-container"> 

      <div class="home-inner-text">
        <h1 class="font-text-small">Hello, I'm </h1>
        <br><br>
        <h1 class="font-text-large">Lunga Momoza </h1>
        <h1 class="font-text-small">Software Developer</h1>
      </div>

      <div class="something">
        <div class="home-button-container">
          <button class="Button">Download CV</button>
          <button class="Button">Contact Info</button>
        </div>

        <div class="home-links-container">
          <a href="">
            <img src="../images/Brown_email_icon-removebg-preview.png" alt="mail" class="social-icon">
          </a>
          <a href="">
            <img src="../images/Brown_Linkedln_icon-removebg-preview.png" alt="linkedin" class="social-icon">
          </a>
          <a href="">
            <img src="../images/Github_Brown_Icon-removebg-preview.png" alt="github" class="social-icon">
          </a>
        </div>
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
#desktop-nav {
  /* max-width: 100vw; */
  width: 100%;
  display: flex;
  justify-content: space-between;
  align-items: center;
  height: 8vh;
  position: fixed;
  background: #664229;
  padding: 0 3rem;
}
.nav-links {
  display: flex;
  justify-content: space-between;
  gap: 3rem;
  align-items: center;
  height: auto;
  list-style-type: none;
}
.nav-links li a {
  text-decoration: none;
  color: #FFF5E2;
}
.logo {
  color: #FFF5E2;
}
.wallpaper {
  position: absolute;
  width: 100vw;
  height: 100vh;
  background: linear-gradient(172deg, #664229 49.8%, #FFF5E2 50%);
  z-index: -1;
}

/* home section  */
.main-container {
  position: relative;
  display: flex;
  flex-direction: row;
  width: 100%;
  height: 100vh;
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
  gap: 7rem;
  width: 60vw;
  height: 100%;
}
.something {
  display: flex;
  flex-direction: column;
  align-items: center;
  justify-content: center;
  gap: 1rem;
}
.home-button-container {
  display: flex;
  gap: 1rem;
  align-items: center;
}
.home-inner-text {
  display: flex;
  flex-direction: column;
  justify-content: center;
  align-items: center;
  /* gap: 1rem; */
}
.Button {
  background-color: #e2b663;
  padding: 1rem 2rem;
  color: white;
  /* min-width: 48px; */
}


.home-button-container {
  width: 300px;
  height: 50px;
  padding: 10px 20px;
  font-size: 18px;
}
.home-links-container {

}
.home-links-container a {
  text-decoration: none;
  color:#664229 ; 
  
}
.social-icon {
  width: 2.2rem;
  text-decoration: none;
  
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
  