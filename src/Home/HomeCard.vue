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
      <img src="../images/IMG_7093.jpg" alt="#" class="about-image">
    </div>

    <div class="about-text-container">
      <h1>About Me</h1>

      <div class="about-row">
        <div class="experience-box">
          <div>
            <h1>Experience</h1>
            <p>
              6+ Months <br>
              Front-End Software Developer <br>
              ABSA/Capaciti <br>
              Venture Capital Intern Consultant <br>
              Crypto Valley Venture Capital, Africa (CVVC). <br>
            </p>
          </div>
          <div>
            <a href="">
              <img src="../images/Experience-icon.png" alt="experience" class="experience-icon">
            </a>
          </div>
        </div>

        <div class="education-box">
          <div>
            <h1>Education</h1>
            <p> 
              Bcom Bachelors Degree. <br>
              Investec Entrepreneurship Certification <br>
              Stellenbosch University Launchlab Startup Incubation <br> 
              Stellenbosch University. <br>
            </p>
          </div>
          <div>
            <a href="">
              <img src="../images/Education-icon.png" alt="education" class="education-icon">
            </a>
          </div>
        </div>
      </div>

      <p>As a highly motivated and dynamic software developer, 
         I am deeply commited to crafting high-end technological solutions and innovative software. 
         My passion lies in creating user-interactive applications that significantly elevate customer experiences. 
         Eager to contribute to the rapid growth of the technological landscape, I aspire to be an integral part of teams driving innovation and 
         excellence in the field of tech and software</p>
    </div>
  </div>

  <!-- experience section -->
  <div class="experience-container">
    <h1>
      Explore My 
      <br> 
      Experience
    </h1>

    <div class="experience-image-container">
      <img src="../images/New Developer icon.jpg" alt="developer-logo" class="developer-icon">
        <!-- floating icons -->
        <a href="">
          <img src="../images/git-icon-removebg-preview.png" alt="language" class="language-icon">
        </a>
    </div>
  </div>

  <!-- projects section -->
  <div class="projects-container">
    <h1>Browse My Projects</h1>
    <h1>Projects</h1>
    <div class="project-row">
      <div class="card">
        <img src="../images/banking app.jpg" alt="" class="card-img">
        <br>
        <h1>Banking App</h1>
      </div>
      <div class="card">
        <img src="../images/healthcare Image icon.png" alt="" class="card-img">
        <br>
        <h1>Healthcare Website</h1>
      </div>
      <div class="card">
        <img src="../images/Tetris Game.png" alt="" class="card-img">
        <br>
        <h1>Tetris Game App</h1>
      </div>
    </div>
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
  z-index: 2;
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
  width: 350px;
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
  min-width: 100vw;
  height: 100vh;
  background-color: #FFF5E2;
}
.about-image {
  border-radius: 50%;
  width: 350px;
  height:440px;
}
.about-image-container {
  display: flex;
  flex-direction: column;
  align-items: center;
  justify-content: center;
  width: 100%;
  max-width: 35vw;
}
.about-text-container {
  display: flex;
  flex-direction: column;
  align-items: flex-start;
  justify-content: center;
  gap: 2rem;
  width: 100%;
  max-width: 65vw;
  padding: 2rem;
  color: #664229;
}
.about-row {
  display: flex;
  width: 100%;
  gap: 1rem;
  color: #FFF5E2;
}
.experience-box, 
.education-box {
  min-width: 50%;
  display: flex;
  gap: 2rem;
  padding: 2rem;
  background-color: #664229;
}
.education-icon,
.experience-icon {
  width: 100px;
}

/* experience section */

.experience-container {
  position: relative;
  display: flex;
  flex-direction: column;
  justify-content: center;
  align-items: center;
  width: 100%;
  min-width: 100vw;
  height: 100vh;
  gap: 2rem;
  background-color: #664229;
}
.experience-image-container {
  width: fit-content;
  height: fit-content;
}
.developer-icon {
  width: 100%;
  min-width: 750px;
}

/* projects section */

.projects-container {
  position: relative;
  display: flex;
  flex-direction: column;
  justify-content: center;
  align-items: center;
  width: 100%;
  min-width: 100vw;
  height: 100vh;
  gap: 2rem;
  background-color: #FFF5E2;
}
.project-row {
  display: flex;
  justify-content: center;
  align-items: center;
  width: 100%;
  min-width: 100vw;
  height: auto;
  gap: 3rem;
}
.card {
  padding-top: 10px;
  border-radius: 5%;
  text-align: center;
  width: 360px;
  height: 320px;
  /* outline: #664229 1px solid; */
  background-color: #c98c60;
}
.card-img {
  width: fit-content;
  max-width: 340px;
  height: 260px;

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
  