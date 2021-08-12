<template>
  <div id="app">
    <link
      rel="stylesheet"
      href="https://use.fontawesome.com/releases/v5.2.0/css/all.css"
      integrity="sha384-hWVjflwFxL6sNzntih27bfxkr27PmbbK/iSvJ+a4+0owXq79v+lsFkW54bOGbiDQ"
      crossorigin="anonymous"
    />
    <link href="https://unpkg.com/aos@2.3.1/dist/aos.css" rel="stylesheet" />
   
    <div id="nav">
      <div class="navbar_text">
        <b-navbar toggleable="sm">
          <div class="container">
            <b-navbar-toggle target="nav-text-collapse"></b-navbar-toggle>

            <b-navbar-brand class="logo"
              ><span>Full </span>
              <span class="logo_text">Stack</span></b-navbar-brand
            >

            <b-collapse id="nav-text-collapse" is-nav>
              <b-navbar-nav>
                <b-nav-text class="mx-4">
                  <a href="#about" class="a_text"> About me</a>
                </b-nav-text>
                <b-nav-text class="mx-4">
                  <a href="#skills" class="a_text"> Skills</a>
                </b-nav-text>
                <b-nav-text class="mx-4">
                  <a href="#projects" class="a_text"> Projects </a>
                </b-nav-text>
                <b-nav-text class="mx-4">
                  <div class="nav_texts">
                    <a href="#contact" class="a_text"> Contact </a>
                  </div>
                </b-nav-text>
              </b-navbar-nav>
            </b-collapse>
          </div>
        </b-navbar>
      </div>

      <top />
    </div>
    <div>
      <middle />
    </div>
    <div>
      <project />
    </div>
    <div>
      <contact />
    </div>
  </div>
</template>

<script>
import top from "@/components/top.vue";
import middle from "@/components/middle.vue";
import project from "@/components/project.vue";
import contact from "@/components/contact.vue";

export default {
  name: "App",
  components: {
    top,
    middle,
    project,
    contact,
  },
};
</script>

<style>
html {
  scroll-behavior: smooth;
}
ul.navbar-nav {
  margin-left: 215px;
}

@media (max-width: 600px) {
  html {
    width: 962px;
  }
  button.navbar-toggler.collapsed {
    font-size: 40px;
}
  .logo {
    font-weight: bold;
    font-size: 60px !important;
  }
  .navbar-brand {
    font-size: 35px;
  }
  li.navbar-text {
    font-size: 30px;
  }
  p.third_white_text {
    font-size: 25px !important;
  }
  p.first_white_text {
    font-size: 35px !important;
  }
  p.second_white_text {
    font-size: 45px !important;
  }
  img.me_img {
    margin-top: 235px !important;
  }
  .navbar_text {
    background: white;
    padding: 0px 35px;
  }
  
  ul.navbar-nav {
    margin-right: 200px;
}
li.navbar-text.mx-4 {
    background: #0db293;
    border-radius: 20px;
    padding: 20px;
    margin-bottom: 5px;
    width:300px;
}
}
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
#nav {
  background: linear-gradient(
    80deg,
    white 50.05%,
    #0db293 40%,
    #0db293 calc(50% + 4px)
  ) !important;
  font-family: "Eczar SemiBold";
}

body {
  margin: 0px !important;
}
div#nav {
  margin-top: -60px;
}
.nav_text {
  display: flex;
}

.logo_text {
  color: #0db293;
}
div#nav-text-collapse {
  display: flex;

  justify-content: center;
}

.logo {
  font-weight: bold;
  font-size: 18px;
}
a {
  text-decoration: none !important;
  color: white !important;
}
a:hover {
  color: black !important;
}
</style>
