<template>
  <div class="container mt-5">
    <p class="skills_small mb-0" id="projects">Portfolio</p>
    <p class="skills_subtitle">Portfolio</p>
    <b-icon icon="reception-0"></b-icon>
    <div data-aos="fade-up">
    <div class="card_container mb-5 mt-5" >
     
        <div class="musicplayer_container" id="musicplayer_container">
           <img
          class="musicplayer"
          id="music"
          src="@/assets/musicplayer.png"
          width="300px"
        />

    
       
      </div>
       
           <containerProject
        image_path="musicplayer.png"
        title="Music Player"
        subtitle="Music player website by Vue.js, it allows the user to play music."
        link="https://github.com/Adalkis/MusicPlayer"
      />

        
     
    </div>
    </div>
    <div data-aos="fade-up">
    <div class="card_container mb-5">
      <div class="musicplayer_container">
        <img
          class="musicplayer"
          id="calories"
          src="@/assets/calories.png"
          width="300px"
        />
      </div>

      <containerProject
        image_path="musicplayer.png"
        title="Calories"
        subtitle="Calories website by vue, bootstrap and laravel. It allows the user to see the calories of each food
          and you can track the amount of calories you consume per day."
        link="https://github.com/Adalkis/MusicPlayer"
      />
    </div>
    </div>

    <div data-aos="fade-up">

    <div class="card_container mb-5">
      <div class="musicplayer_container">
        <img
          class="musicplayer"
          id="desahogate"
          src="@/assets/desahogate.png"
          width="308px"
          height="200px"
        />
      </div>

      <containerProject
        image_path="musicplayer.png"
        title="Desahogate"
        subtitle="Desahogate website by vue, bootstrap and laravel. It allows the user to share stories and to comment
          them."
        link="https://github.com/Adalkis/MusicPlayer"
      />
    </div>
    </div>
  </div>
</template>

<script>
import containerProject from "./containerProjects";
export default {
  name: "project",
  components: { containerProject },
};
</script>
<style scoped>
@media (max-width:600px){
  p#projects {
    font-size: 20px;
    font-weight: bold;
}
p.skills_subtitle {
    font-size: 40px !important;
}
  .musicplayer_container{
    position: unset !important;
    width: 950px !important;
  }
  #musicplayer_container{
    width: 900px !important;
  }
  .card_container{
    display: block !important;
  }
  .musicplayer_image {
    width: 995px;
    position: absolute;
}
img{
  width: 700px;
}
.musicplayer {
    position: relative;
}
img#desahogate {
    height: 551px;
    width: 750px;
}
}
p.skills_small.mb-0 {
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
.musicplayer_container {
  width: 100px;
  position: absolute;
}
.card_container {
  display: flex;
}
img.musicplayer {
  margin-top: -15px;
}
img#calories {
  margin-top: -8px;
}
img#desahogate {
  margin-top: 10px;
}
.card-body {
  width: 100px;
}
img#music {
  margin-top: 7px;
}

</style>