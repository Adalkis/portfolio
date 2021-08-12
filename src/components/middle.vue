<template>
  <div class="container">
    <div class="container_about_title">
      <p class="about_title mt-5">About <span class="about_title" id="about"> Me</span></p>
    </div>
    <div data-aos="fade-up" >
      <p class="about_subtitle mt-5 mb-5 mx-5" >
      I'm a full stack software developer, I love learning new
      techonologies in order to be updated. An apparent website makes me feel
      comfortable and secure, so this is what I try to do when I create one. I
      value simplicity and that's one of the things that I offer. If I'm not
      coding, I'll be watching series or fixing some issues about networking.
    </p>
    </div>
  
    <div data-aos="fade-up">

    <div class="mt-5" id="skills">
      <p class="skills_small mb-0" >Skills</p>
      <p class="skills_subtitle">Skills</p>
      <b-icon icon="reception-0"></b-icon>
 
      <div class="icons mt-5">
        <containerIcon icon_name="fab fa-html5" text="HTML5"></containerIcon>
        <containerIcon icon_name="fab fa-css3-alt" text="CSS3"></containerIcon>
        <containerIcon
          icon_name="fas fa-mobile"
          text="Responsive Design"
        ></containerIcon>
        <containerIcon icon_name="fab fa-js" text="JavaScript"></containerIcon>
      </div>
      <div class="icons mt-3">
        <containerIcon icon_name="fab fa-php" text="PHP"></containerIcon>
        <containerIcon
          icon_name="fab fa-laravel"
          text="Laravel"
        ></containerIcon>
        <containerIcon
          icon_name="fab fa-wordpress"
          text="Wordpress"
        ></containerIcon>
        <containerIcon icon_name="fab fa-github" text="GitHub"></containerIcon>
      </div>
      <div class="icons">
        <containerIcon icon_name="fab fa-vuejs" text="Vuejs"></containerIcon>
        <containerIcon icon_name="fas fa-database" text="MySql"></containerIcon>
        <containerIcon
          icon_name="fas fa-bootstrap"
          text="Bootstrap"
          icon_text="B"
        ></containerIcon>
        <containerIcon  class="mb-3" icon_name="fab fa-quora" text="Quasar"></containerIcon>
      </div>
    </div>
      </div>
  </div>
</template>

<script>

import containerIcon from "./containerIcon";
export default {
  name: "middle",
  components: { containerIcon },
};
</script>
<style scoped>
@media  (max-width:600px){
 
  .about_subtitle.mt-5.mb-5 {
    font-size: 40px;
}
.skills_subtitle {
    font-size: 60px !important;
}
.skills_small.mb-0 {
    font-size: 20px !important;
}
.about_title.mt-5 {
  font-size: 60px !important;
  font-weight: bold;
}
.about_subtitle {
  font-size: 40px ;
  align-items: center;
}

    
}

.about_title.mt-5 {
  font-size: 30px;
  font-weight: bold;
}

span.about_title {
  color: #0db293;
}
.about_subtitle {
  font-size: 24px ;
  align-items: center;
}
.skills_small.mb-0 {
  font-size: 15px;
  color: #0db293;
}
.skills_subtitle {
  font-size: 30px;
  font-weight: bold;
  text-decoration: dotted;
  margin-bottom: -25px;
}

svg.bi-reception0.b-icon.bi {
  font-size: 40px;
  color: #0db293;
}
.icons {
  display: flex;
  justify-content: space-evenly;
}
i {
  font-size: 40px;
  background: white;
  color: #0db293;
  padding: 16px 25px 16px 25px;
  border-top-left-radius: 20px;
  border-top-right-radius: 20px;
  border-bottom-left-radius: 20px;
}
svg.bi-bootstrap.b-icon.bi {
  font-size: 80px;
  background: #0db293;
  color: white;
  padding: 12px 20px 12px 20px;
  border-top-left-radius: 20px;
  border-top-right-radius: 20px;
  border-bottom-left-radius: 20px;
}
.laravel_icon {
  margin: 0 0 0 -18px;
}
._icons {
  background: #0db293;
  padding: 50px 80px 50px 80px;
  border-radius: 20px;
}
</style>