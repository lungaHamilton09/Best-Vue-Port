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
      <div class="group-9">
        <div class="group-8">
          <div class="group-7">
            <div class="lunga-momoza">Lunga Momoza</div>
            <div class="about">About</div>
            <div class="experience">Experience</div>
            <div class="projects">Projects</div>
            <div class="contact">Contact</div>
          </div>
        </div>
      </div>
    </div>
    <div class="hello-i-m">Hello, I’m</div>
    <div class="lunga-momoza2">Lunga Momoza</div>
    <div class="software-developer">Software Developer</div>
    <!-- <img class="ellipse-1" src="ellipse-10.png" /> -->
    <!-- <div class="download-cv">Download CV</div>
    <div class="contact-info">Contact Info</div>
    <img class="download-icon-1" src="download-icon-10.png" />
    <img class="brown-linkedln-icon-1" src="brown-linkedln-icon-10.png" />
    <img class="brown-email-icon-1" src="brown-email-icon-10.png" />
    <img class="github-brown-icon-1" src="github-brown-icon-10.png" />
  </div> -->
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
.home,
.home * {
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
  width: 950px;
  height: 600px;
  position: absolute;
  left: 0px;
  top: 0px;
}
.rectangle-13 {
  width: 959px;
  height: 369px;
  position: absolute;
  left: -9px;
  top: 0px;
  overflow: visible;
}
.rectangle-11 {
  width: 127px;
  height: 37px;
  position: absolute;
  left: 473px;
  top: 332px;
  overflow: visible;
}
.contact-info {
  width: 117px;
  height: 37px;
  position: absolute;
  left: 679px;
  top: 332px;
  overflow: visible;
}
.group-10 {
  position: absolute;
  inset: 0;
}
.group-9 {
  width: 862px;
  height: 19px;
  position: static;
}
.group-8 {
  width: 862px;
  height: 19px;
  position: static;
}
.group-7 {
  width: 862px;
  height: 19px;
  position: static;
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
.about {
  color: #efd6b5;
  text-align: left;
  font-family: "Inter-Bold", sans-serif;
  font-size: 16px;
  font-weight: 700;
  position: absolute;
  left: 541px;
  top: 24px;
}
.experience {
  color: #efd6b5;
  text-align: left;
  font-family: "Inter-Bold", sans-serif;
  font-size: 16px;
  font-weight: 700;
  position: absolute;
  left: 639px;
  top: 24px;
}
.projects {
  color: #efd6b5;
  text-align: left;
  font-family: "Inter-Bold", sans-serif;
  font-size: 16px;
  font-weight: 700;
  position: absolute;
  left: 751px;
  top: 24px;
}
.contact {
  color: #efd6b5;
  text-align: left;
  font-family: "Inter-Bold", sans-serif;
  font-size: 16px;
  font-weight: 700;
  position: absolute;
  left: 849px;
  top: 24px;
}
.hello-i-m {
  color: #cb8f65;
  text-align: left;
  font-family: "Inter-SemiBold", sans-serif;
  font-size: 20px;
  font-weight: 600;
  position: absolute;
  left: 556px;
  top: 123px;
}
.lunga-momoza2 {
  color: #d2b48c;
  text-align: left;
  font-family: "Inter-ExtraBold", sans-serif;
  font-size: 36px;
  font-weight: 800;
  position: absolute;
  left: 500px;
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
  left: 526px;
  top: 226px;
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
  left: 699px;
  top: 346px;
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
.brown-linkedln-icon-1 {
  width: 46px;
  height: 42px;
  position: absolute;
  left: 611px;
  top: 427px;
  object-fit: cover;
}
.brown-email-icon-1 {
  width: 51px;
  height: 40px;
  position: absolute;
  left: 547px;
  top: 428px;
  object-fit: cover;
}
.github-brown-icon-1 {
  width: 42px;
  height: 42px;
  position: absolute;
  left: 673px;
  top: 428px;
  object-fit: cover;
}
</style>
