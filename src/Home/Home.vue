<template>
  <div class="home">
    <div class="rectangle-20"></div>
    <svg
      class="rectangle-13"
      width="959"
      height="369"
      viewBox="0 0 959 369"
      fill="none"
      xmlns="http://www.w3.org/2000/svg"
    >
      <path d="M0 0H959V258.5L0 369V0Z" fill="#664229" />
    </svg>
  </div>
    <svg
      class="rectangle-11"
      width="127"
      height="37"
      viewBox="0 0 127 37"
      fill="none"
      xmlns="http://www.w3.org/2000/svg"
    >
      <g filter="url(#filter0_d_50_103)">
        <path d="M0 0H127V37H0V0Z" fill="#D2B48C" />
      </g>
      <defs>
        <filter
          id="filter0_d_50_103"
          x="-5"
          y="-1"
          width="137"
          height="47"
          filterUnits="userSpaceOnUse"
          color-interpolation-filters="sRGB"
        >
          <feFlood flood-opacity="0" result="BackgroundImageFix" />
          <feColorMatrix
            in="SourceAlpha"
            type="matrix"
            values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"
            result="hardAlpha"
          />
          <feOffset dy="4" />
          <feGaussianBlur stdDeviation="2.5" />
          <feComposite in2="hardAlpha" operator="out" />
          <feColorMatrix
            type="matrix"
            values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0.25 0"
          />
          <feBlend
            mode="normal"
            in2="BackgroundImageFix"
            result="effect1_dropShadow_50_103"
          />
          <feBlend
            mode="normal"
            in="SourceGraphic"
            in2="effect1_dropShadow_50_103"
            result="shape"
          />
        </filter>
      </defs>
    </svg>
    <svg
      class="contact-info"
      width="117"
      height="37"
      viewBox="0 0 117 37"
      fill="none"
      xmlns="http://www.w3.org/2000/svg"
    >
      <g filter="url(#filter0_d_50_102)">
        <path d="M0 0H117V37H0V0Z" fill="#D2B48C" />
      </g>
      <defs>
        <filter
          id="filter0_d_50_102"
          x="-5"
          y="-1"
          width="127"
          height="47"
          filterUnits="userSpaceOnUse"
          color-interpolation-filters="sRGB"
        >
          <feFlood flood-opacity="0" result="BackgroundImageFix" />
          <feColorMatrix
            in="SourceAlpha"
            type="matrix"
            values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"
            result="hardAlpha"
          />
          <feOffset dy="4" />
          <feGaussianBlur stdDeviation="2.5" />
          <feComposite in2="hardAlpha" operator="out" />
          <feColorMatrix
            type="matrix"
            values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0.25 0"
          />
          <feBlend
            mode="normal"
            in2="BackgroundImageFix"
            result="effect1_dropShadow_50_102"
          />
          <feBlend
            mode="normal"
            in="SourceGraphic"
            in2="effect1_dropShadow_50_102"
            result="shape"
          />
        </filter>
      </defs>
    </svg>
    <div class="group-10">
      <div class="lunga-momoza">Lunga Momoza</div>
          <div class="group-7">
            <div class="about">
              <a href="#about">About</a></div>
            <div class="experience">
              <a href="#experience">Experience</a></div>
            <div class="projects">
              <a href="#projects">Projects</a></div>
            <div class="contact">
              <a href="#contact">Contact</a></div>
          </div>
    </div>
    <div class="home-content">
  <div class="hello-i-m">Hello, I’m</div>
  <div class="lunga-momoza2">Lunga Momoza</div>
  <div class="software-developer">Software Developer</div>
  <img class="ellipse-1" src="../public/ellipse-10.png" />
  <button class="download-cv">Download CV</button>
  <button class="contact-info">Contact Info</button>
  <div class="download-icon-1"></div>
  <div class="brown-linkedln-icon-1"><i class='bx bxl-linkedin-square'></i></div>
  <div class="brown-email-icon-1" ><i class='bx bx-envelope'></i></div>
  <div class="github-brown-icon-1"><i class='bx bxl-github' ></i></div> 
</div>
</template>
<script>
export default {
  name: "Home",
  components: {},
  props: {},
  data() {},
};
</script>
<style scoped>
@import 'https://unpkg.com/boxicons@2.1.4/css/boxicons.min.css';
.home,
 * {
  box-sizing: border-box;
}
.home {
  background: #ffffff;
  border-style: solid;
  border-color: #000000;
  border-width: 1px;
  height: 100vh;
  width: 100%;
  position: relative;
  overflow: hidden;
}
.rectangle-20 {
  background: #fff5e2;
  width: 100%;
  height: 100vh;
  position: absolute;
  left: 0px;
  top: 0px;
}
.rectangle-13 {
  width: 100%;
  height: auto;
  position: absolute;
  left: -9px;
  top: 0px;
  overflow: visible;
}

.contact-info {
  width: 117px;
  height: 37px;
  position: absolute;
  left: 849px;
  top: 339px;
  overflow: visible;
}
.group-10 {
  position: absolute;
  top: 0;
  width: 100%;
}
.group-7 {
  width: 862px;
  height: 19px;
  text-align: right;
}
.lunga-momoza {
  color: #efd6b5;
  text-align: left;
  font-family: "Inter-Bold", sans-serif;
  font-size: 16px;
  font-weight: 700;
  position: absolute;
  left: 50px;
  top: 24px;
}
.about a {
  color: #efd6b5;
  text-align: left;
  font-family: "Inter-Bold", sans-serif;
  font-size: 16px;
  font-weight: 700;
  position: absolute;
  right: 700px;
  top: 24px;
}
.experience a {
  color: #efd6b5;
  text-align: left;
  font-family: "Inter-Bold", sans-serif;
  font-size: 16px;
  font-weight: 700;
  position: absolute;
  right: 500px;
  top: 24px;
}
.projects a {
  color: #efd6b5;
  text-align: left;
  font-family: "Inter-Bold", sans-serif;
  font-size: 16px;
  font-weight: 700;
  position: absolute;
  right: 320px;
  top: 24px;
}
.contact a {
  color: #efd6b5;
  text-align: left;
  font-family: "Inter-Bold", sans-serif;
  font-size: 16px;
  font-weight: 700;
  position: absolute;
  right: 150px;
  top: 24px;
}
.hello-i-m {
  color: #cb8f65;
  text-align: left;
  font-family: "Inter-SemiBold", sans-serif;
  font-size: 20px;
  font-weight: 600;
  position: absolute;
  right: 650px;
  top: 123px;
}
.lunga-momoza2 {
  color: #d2b48c;
  text-align: left;
  font-family: "Inter-ExtraBold", sans-serif;
  font-size: 36px;
  font-weight: 800;
  position: absolute;
  right: 500px;
  top: 171px;
  -webkit-text-stroke: 1px transparent;
}
.software-developer {
  color: #cb8f65;
  text-align: left;
  font-family: "Inter-SemiBold", sans-serif;
  font-size: 20px;
  font-weight: 600;
  position: absolute;
  right: 575px;
  top: 240px;
  -webkit-text-stroke: 1px transparent;
}
.ellipse-1 {
  border-radius: 50%;
  width: 277px;
  height: 341px;
  position: absolute;
  left: 69px;
  top: 107px;
  box-shadow: 0px 4px 10px 3px rgba(255, 255, 255, 0.25);
  object-fit: cover;
}
.download-cv {
  color: #f5f5f5;
  text-align: left;
  font-family: "Inter-Regular", sans-serif;
  font-size: 12px;
  font-weight: 400;
  position: absolute;
  left: 507px;
  top: 343px;
}
.contact-info {
  color: #f5f5f5;
  text-align: left;
  font-family: "Inter-Regular", sans-serif;
  font-size: 12px;
  font-weight: 400;
  position: absolute;
  left: 849px;
  top: px;
}

.download-icon-1 {
  border-radius: 15px;
  width: 15px;
  height: 15px;
  position: absolute;
  left: 481px;
  top: 343px;
  object-fit: cover;
}
.brown-linkedln-icon-1 i {
  color: #000000;
  font-size: 2rem;
  position: absolute;
  left: 611px;
  top: 400px;
  right: 700px;
}
.brown-email-icon-1 i {
  color: #FFF5E2;  
  font-size: 2rem;
  position: absolute;
  top: 400px;
  right: 700px;
}
.github-brown-icon-1 i {
  color: #ffffff;
  font-size: 2rem;
  position: absolute;
  left: 755px;
  top: 420px;  
  
}
</style>
