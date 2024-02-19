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
        <br><br>
        <h1 class="font-text-small">Software Developer</h1>
        <br><br>
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

    <div class="about-image-container">
      <img src="../images/IMG_7093.jpg" alt="#" class="hero-image">
    </div>

    <div class="about-text-container">
      <h1>Heading</h1>
  
      <div class="experience-boxes">
      <div>Experience</div>
      <a href="">
        <img src="../images/Experience-icon.png" alt="experience" class="experience-icon">
      </a>
      <p>6+ Months
         Frontend 
         Development.</p>

      <div>Education</div>
      <a href="">
        <img src="../images/Education-icon.png" alt="education" class="education-icon">
      </a>
      <p> BCOM. 
          Bachelors 
          Degree.</p>
      </div>
      
      <p>As a highly motivated and dynamic software developer, I am deeply commited to crafting high-end technological solutions and innovative software. My passion lies in creating user-interactive applications that significantly elevate customer experiences. Eager to contribute to the rapid growth of the technological landscape, I aspire to be an integral part of teams driving innovation and excellence in the field of tech and software</p>
    </div>
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
  background: linear-gradient(175deg, #664229 49.8%, #FFF5E2 50%);
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
  justify-content: flex-start;
  align-items: center;
  gap: 3rem;
  padding-top: 20vh;
  width: 60vw;
  height: 100vh;
}
.something {
  display: flex;
  flex-direction: column;
  align-items: center;
  justify-content: flex-start;
  gap: 3rem;
}
.home-button-container {
  display: flex;
  gap: 2rem;
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
  background-color: #D2B48C;
  padding: 1rem 2rem;
  color: white;
  min-width: 30px;
  /* min-width: 48px; */
}

.home-button-container {
  width: 100%;
}
.home-links-container {
  display: flex;
  align-items: center;
  justify-content: space-evenly;
  gap: 2rem;
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
.about-container {
display: flex;
flex-direction: row;
width: 100%;
height: 100vh;
}
.hero-image {
  width: 60%;
  height: 60%;
  border-radius: 50%;  
}
.about-text-container {
  display: flex;
  flex-direction: column;
  align-items: center;
  justify-content: flex-start;
  gap: 3rem;

}




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
  