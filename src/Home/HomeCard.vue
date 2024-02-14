<template>
    <div class="about">
      <div class="rectangle-19"></div>
      <div class="rectangle-14"></div>
      <svg class="rectangle-13" width="950" height="369"></svg>
      <div class="rectangle-5"></div>
      <img class="picture" src="../images/img_7093.png" />
      <div class="about-me">
        <span>
          <span class="about-me-span">About</span>
          <span class="about-me-span2"></span>
          <span class="about-me-span3">Me</span>
          <span class="about-me-span4"></span>
        </span>
      </div>
      <div class="experience">Experience</div>
      <div class="education">
        <span>
          <span class="education-span">Education</span>
          <span class="education-span2"></span>
        </span>
      </div>
      <div class="_6-months">6+ Months</div>
      <div class="text"></div>
      <div class="bcom-bachelors-degree">Bcom Bachelors Degree</div>
      <div
        class="as-a-highly-motivated-and-dynamic-software-developer-i-am-deeply-committed-to-crafting-high-end-technological-solutions-and-innovative-software-my-passion-lies-in-creating-user-interactive-applications-that-significantly-elevate-customer-experiences-eager-to-contribute-to-rapid-growth-of-the-technological-landscape-i-aspire-to-be-an-integral-part-of-teams-driving-innovation-and-excellence-in-the-field-of-tech-and-software"
      >
        As a highly motivated and dynamic software developer, I am deeply
        committed to crafting high-end technological solutions and innovative
        <br />
        software. My passion lies in creating user-interactive applications that
        <br />
        significantly elevate customer experiences. Eager to contribute to rapid
        <br />
        growth of the technological landscape, I aspire to be an integral part of
        teams driving innovation and excellence in the field of tech and software.
        <br />
      </div>
      <img class="education-icon" src="../images/Education-icon.png" />
      <img class="experience-icon" src="../images/Experience-icon.png" />
      <div class="group-10">
        <div class="group-9">
          <div class="group-8">
            <div class="group-7">
              <div class="lunga-momoza">Lunga Momoza</div>
              <div class="about2">About</div>
              <!-- <div class="experience-icon">Experience</div> -->
              <div class="projects">Projects</div>
              <div class="contact">Contact</div>
            </div>
          </div>
        </div>
      </div>
      <div class="stellenbosch-university">Stellenbosch University</div>
      <div class="frontend-developemnt">Frontend Developemnt</div>
      <div class="vc-intern-consultant">VC Intern Consultant</div>
    </div>
  </template>
  <script>
  export default {
    name: "About",
    components: {},
    props: {},
    data() {},
  };
  </script>
  <style scoped>
  .about,
  .about * {
    box-sizing: border-box;
  }
  .about {
    background: #ffffff;
    border-style: solid;
    border-color: #000000;
    border-width: 1px;
    height: 100vh;
    width: 100%;
    position: relative;
    overflow: hidden;
  }
  .rectangle-19 {
    background: #fff5e2;
    width: 100%;
    height: 100vh;
    position: absolute;
    left: 0px;
    top: 0px;
  }
  .rectangle-14 {
    background: #664229;
    width: 260px;
    height: 100px;
    position: absolute;
    left: 610px;
    top: 210px;
    box-shadow: 0px 4px 4px 0px rgba(0, 0, 0, 0.25),
      0px 4px 4px 0px rgba(0, 0, 0, 0.25);
  }
  .rectangle-13 {
    width: 950px;
    height: 369px;
    position: absolute;
    left: 0px;
    top: -12px;
    overflow: visible;
  }
  .rectangle-5 {
    background: #664229;
    width: 260px;
    height: 100px;
    position: absolute;
    left: 910px;
    top: 210px;
    box-shadow: 0px 4px 4px 0px rgba(0, 0, 0, 0.25),
      0px 4px 4px 0px rgba(0, 0, 0, 0.25);
  }
  .picture {
    border-radius: 50%;
    width: 300px;
    height: 341px;
    position: absolute;
    left: 48px;
    top: 113px;
    object-fit: cover;
  }
  .about-me {
    text-align: left;
    font-family: "Inter-Bold", sans-serif;
    font-size: 32px;
    font-weight: 700;
    position: absolute;
    left: 385px;
    top: 124px;
  }
  .about-me-span {
    color: #664229;
    font-family: "Inter-Bold", sans-serif;
    font-size: 32px;
    font-weight: 700;
  }
  .about-me-span2 {
    color: #ffffff;
    font-family: "Inter-Bold", sans-serif;
    font-size: 32px;
    font-weight: 700;
  }
  .about-me-span3 {
    color: #664229;
    font-family: "Inter-Bold", sans-serif;
    font-size: 32px;
    font-weight: 700;
  }
  .about-me-span4 {
    color: #ffffff;
    font-family: "Inter-Bold", sans-serif;
    font-size: 32px;
    font-weight: 700;
  }
  .experience {
    color: #ffffff;
    text-align: left;
    font-family: "Inter-Bold", sans-serif;
    font-size: 16px;
    font-weight: 700;
    position: absolute;
    left: 408px;
    top: 218px;
  }
  .education {
    text-align: left;
    font-family: "Inter-Bold", sans-serif;
    font-size: 16px;
    font-weight: 700;
    position: absolute;
    left: 732px;
    top: 218px;
  }
  .education-span {
    color: #ffffff;
    font-family: "Inter-Bold", sans-serif;
    font-size: 16px;
    font-weight: 700;
  }
  .education-span2 {
    color: #000000;
    font-family: "Inter-Bold", sans-serif;
    font-size: 16px;
    font-weight: 700;
  }
  ._6-months {
    color: #ffffff;
    text-align: left;
    font-family: "Inter-Bold", sans-serif;
    font-size: 14px;
    font-weight: 700;
    position: absolute;
    left: 388px;
    top: 246px;
  }
  .text {
    color: #000000;
    text-align: left;
    font-family: "Inter-Regular", sans-serif;
    font-size: 12px;
    font-weight: 400;
    position: absolute;
    left: 408px;
    top: 357px;
  }
  .bcom-bachelors-degree {
    color: #ffffff;
    text-align: left;
    font-family: "Inter-Bold", sans-serif;
    font-size: 14px;
    font-weight: 700;
    position: absolute;
    left: 670px;
    top: 238px;
  }
  .as-a-highly-motivated-and-dynamic-software-developer-i-am-deeply-committed-to-crafting-high-end-technological-solutions-and-innovative-software-my-passion-lies-in-creating-user-interactive-applications-that-significantly-elevate-customer-experiences-eager-to-contribute-to-rapid-growth-of-the-technological-landscape-i-aspire-to-be-an-integral-part-of-teams-driving-innovation-and-excellence-in-the-field-of-tech-and-software {
    color: #000000;
    text-align: left;
    font-family: "Inter-Medium", sans-serif;
    font-size: 12px;
    font-weight: 500;
    position: absolute;
    left: 384px;
    top: 331px;
    width: 427px;
    height: 105px;
  }
  .education-icon {
    width: 56px;
    height: 46px;
    position: absolute;
    left: 859px;
    top: 223px;
    object-fit: cover;
  }
  .experience-icon  {
    width: 90px;
    height: 72px;
    position: absolute;
    left: 550px;
    top: 218px;
    object-fit: cover;
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
    color: #664229;
    text-align: left;
    font-family: "Inter-Bold", sans-serif;
    font-size: 16px;
    font-weight: 700;
    position: absolute;
    left: 34px;
    top: 23px;
  }
  .about2 {
    color: #664229;
    text-align: left;
    font-family: "Inter-Bold", sans-serif;
    font-size: 16px;
    font-weight: 700;
    position: absolute;
    left: 525px;
    top: 23px;
  }
  .experience2 {
    color: #664229;
    text-align: left;
    font-family: "Inter-Bold", sans-serif;
    font-size: 16px;
    font-weight: 700;
    position: absolute;
    left: 623px;
    top: 23px;
  }
  .projects {
    color: #664229;
    text-align: left;
    font-family: "Inter-Bold", sans-serif;
    font-size: 16px;
    font-weight: 700;
    position: absolute;
    left: 735px;
    top: 23px;
  }
  .contact {
    color: #664229;
    text-align: left;
    font-family: "Inter-Bold", sans-serif;
    font-size: 16px;
    font-weight: 700;
    position: absolute;
    left: 833px;
    top: 23px;
  }
  .stellenbosch-university {
    color: #ffffff;
    text-align: left;
    font-family: "Inter-Bold", sans-serif;
    font-size: 14px;
    font-weight: 700;
    position: absolute;
    left: 670px;
    top: 260px;
  }
  .frontend-developemnt {
    color: #ffffff;
    text-align: left;
    font-family: "Inter-Bold", sans-serif;
    font-size: 14px;
    font-weight: 700;
    position: absolute;
    left: 388px;
    top: 264px;
  }
  .vc-intern-consultant {
    color: #ffffff;
    text-align: left;
    font-family: "Inter-Bold", sans-serif;
    font-size: 14px;
    font-weight: 700;
    position: absolute;
    left: 391px;
    top: 284px;
  }
  </style>
  