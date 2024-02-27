<template>
  <nav id="desktop-nav">
    <div class="logo">Lunga Momoza</div>
    <div>
      <ul class="nav-links">
        <li><a href="#home">Home</a></li>
        <li><a href="#about">About</a></li>
        <li><a href="#experience">Experience</a></li>
        <li><a href="#projects">Projects</a></li>
        <li><a href="#contact">Contact</a></li>
      </ul>
    </div>
  </nav>

  
<!-- home section  -->
  <div class="main-container" id="home">
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
    
          <button class="Button" href="../images/cv.pdf" @click="downloadCV">Download CV</button>
          <button class="Button"><a href="#co"></a>Contact Info</button>
        </div> 

        <div class="home-links-container">
          <a href="https://www.linkedin.com/in/lunga-hamilton-momoza-94bb181a7/" target="_blank">
            <img src="../images/Brown_email_icon-removebg-preview.png" alt="mail" class="social-icon">
          </a>
          <a href="https://www.linkedin.com/in/lunga-hamilton-momoza-94bb181a7/" target="_blank">
            <img src="../images/Brown_Linkedln_icon-removebg-preview.png" alt="linkedin" class="social-icon">
          </a>
          <a href="https://github.com/lungaHamilton09/Personal-Portfolio" target="_blank">
            <img src="../images/Github_Brown_Icon-removebg-preview.png" alt="github" class="social-icon">
          </a>
        </div>
      </div>



    </div>
  </div>



  <!-- About section -->
  <div class="about-container" id="about">

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
  <div class="experience-container" id="experience">
    <h1>
      Explore My 
      <br> 
      Experience
    </h1>

    <div class="experience-image-container">
      <img src="../images/New_Developer_icon-removebg-preview (1).png" alt="developer-logo" class="developer-icon">
        <!-- floating icons -->
        <div class="float-icon">
          <img src="../images/CSS_Icon-removebg-preview (1).png" class="css-icon" alt="">
        </div>
        <div class="float-icon">
          <img src="../images/JS_Icon-removebg-preview.png" class="js-icon" alt="">
        </div>
        <div class="float-icon">
          <img src="../images/Material_UI_icon-removebg-preview (1).png" class="material-icon" alt="">
        </div>
        <div class="float-icon">
          <img src="../images/git_icon-removebg-preview-removebg-preview.png" class="git-icon" alt="">
        </div>
        <div class="float-icon">
          <img src="../images/Node_JS-removebg-preview.png" class="node-icon" alt="">
        </div>
    </div>
  </div>

  <!-- projects section -->
  <div class="projects-container" id="projects">
    <h1>Browse My Projects</h1>
    <h1>Projects</h1>
    <div class="project-row">
      <div class="card">
  <a href="https://github.com/TshepoShale/pythonProject1" target="_blank">
    <img src="../images/banking app.jpg" alt="Banking App" class="card-img">
  </a>
  <br>
  <h1>Banking App</h1>
</div>

      <div class="card">
        <a href="https://keen-tapioca-29c1f9.netlify.app/" target="_blank">
        <img src="../images/healthcare Image icon.png" alt="Healthcare Website" class="card-img">
      </a>
        <br>
        <h1>Healthcare Website</h1>
      </div>
      <div class="card">
        <a href="https://tetris-game-mookgo.netlify.app/game.html" target="_blank">
        <img src="../images/Tetris Game.png" alt="" class="card-img">
        </a>
        <br>
        <h1>Tetris Game App</h1>
      </div>
    </div>
  </div>

  <!-- contact section -->
  <div class="contact-container" id="contact">

    <div class="form-container">
      <div class="form">
      <h1>Send Me A Message</h1>
      <br>
      <form action="#" method="#">
        <input type="text" id="name" name="name" required placeholder="Name">
        <input type="email" id="email" name="email" required placeholder="Email">
        <textarea id="message" name="message" rows="4" required placeholder="message"></textarea>
        <br>
        <button type="submit">Send</button>
      </form>
      <div class="cube">
        <h1 class="font-text-small">Drop In My Space</h1>
        <br>
        <br>
        <h1 class="font-text-medium">I am located in Cape Town the hub of fast growing talent and companies</h1>
        <br>
        <h1 class="font-text-xsmall align-center transform-uppercase">Khayelitsha, Cape Town</h1>
        <br>
        <h1 class="font-text-xsmall align-center transform-uppercase">Blessedlungamomoza@gmail.com</h1>
        <br>
        <div class="flex-row align-center">
          <h1 class="font-text-xsmall transform-uppercase">+27 67 795 1145</h1>
          <img src="../images/brown_telephone_icon-removebg-preview (1).png" alt="telepnone" class="telephone-icon">
        </div>
      </div>
    </div>

    </div>

  </div>

 
</template>

<script>
export default {
  name: 'HomeCard',
  methods: {
    downloadCV() {
      const cvUrl = "../images/cv.pdf";
      const anchor = document.createElement("a");
      anchor.href = cvUrl;
      anchor.download = "cv.pdf";
      anchor.click();
    }
  }
}
</script>

<style scoped>

html, * {
  scroll-behavior: smooth;
}
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

/* home section  */
@media screen and (max-width: 768px) {

  .main-container{
    flex-direction: column;
    height: 100%;
    justify-content: center;
    align-items: center;
    padding-top: 15%;
  }

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
@media screen and (max-width: 768px) {

.about-container{
  flex-direction: column;
  height: 100%;
  justify-content: center;
  align-items: center;
  padding-top: 15%;
  display: flex;
}
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
  position: relative;
  width: fit-content;
  height: fit-content;
}
.developer-icon {
  width: 100%;
  min-width: 750px;
}
.css-icon {
  width: 5rem;
  position: absolute;
  top: 0;
  right: 0;
}
.js-icon {
  width: 7rem;
  position: absolute;
  top: 0;
  left: 0;
}
.material-icon {
  width: 7rem;
  position: absolute;
  left: -85px;
  top: 40%;
}
.git-icon {
  width: 4rem;
  position: absolute;
  left: -150px;
  top: 70%;
}
.node-icon {
  width: 8rem;
  position: absolute;
  right: -150px;
  bottom: 25%;
}
@media screen and (max-width: 768px) {

.experience-container{
  flex-direction: column;
  height: 100%;
  justify-content: center;
  align-items: center;
  padding-top: 15%;
}
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
  background-color: #664229; 
}
.card-img {
  width: fit-content;
  max-width: 340px;
  height: 260px;

}
@media screen and (max-width: 768px) {

.project-container{
  flex-direction: column;
  height: 100%;
  justify-content: center;
  align-items: center;
  padding-top: 15%;
}
}

/* contact section */
.contact-container {
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
@media screen and (max-width: 768px) {

.contact-container{
  flex-direction: column;
  height: 100%;
  justify-content: center;
  align-items: center;
  padding-top: 15%;
  display: flex;
}
}
/* form */
.contact-container {

    display: flex;
    justify-content: center;
    align-items: center;
    height: 100vh;
  }
  form {
    height: 100%;
  }
  .form {
    background-color: #fff;
    padding: 30px;
    border-radius: 10px;
    max-width: 650px;
    height: 100%;
    min-height: 550px;
    box-shadow: 0 0 20px rgba(0, 0, 0, 0.1);
  }
  input[type="text"],
  input[type="email"],
  textarea {
    width: 100%;
    max-width: 370px;
    padding: 10px;
    margin-bottom: 15px;
    border: 1px solid #ccc;
    border-radius: 25px;
    box-sizing: border-box;
    font-size: 16px;
  }
  textarea {
    resize: vertical;
  }
  button {
    background-color: #4caf50;
    color: #fff;
    padding: 12px 20px;
    border: none;
    border-radius: 6px;
    cursor: pointer;
    font-size: 16px;
    transition: background-color 0.3s ease;
  }
  button:hover {
    background-color: #45a049;
  }
  ::placeholder {
    color: #999;
  }
  .form-container {
    position: relative;
  }
/* .box {
  padding-top: 10px;
  border-radius: 5%;
  text-align: center;
  width: 360px;
  height: 320px;
  background-color: #FFF5E2;
  left: 100%;
} */
.cube {
  position: absolute;
  padding-top: 10px;
  border-radius: 5%;
  text-align: center;
  width: 420px;
  height: 500px;  
  background-color: #FFF5E2;
  top: 20%;
  right: -30%;
  font-size: 1rem;
  padding: 1.5rem;
  display: flex;
  flex-direction: column;
  align-items: flex-start;
  justify-content: flex-start;
  gap: 1rem;
}
.telephone-icon {
  width: 50px;

}
.flex-row {
  display: flex;
  flex-direction: row-reverse;
  align-items: center;
  gap: 1rem;
}
.align-center {
  padding-left: 75px;
}
.transform-uppercase {
  text-transform: uppercase;
}

/* font styles */
.font-text-xsmall {
  font-family: Arial, Helvetica, sans-serif;
  font-size: 12px;
  line-height: 1;
}
.font-text-medium {
  font-family: Arial, Helvetica, sans-serif;
  font-size: 1.5rem;
  line-height: 1;
}
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
  