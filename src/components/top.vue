<template>
  <div class="container_top container">
    <div class="white">
      <div class="white_text text-start">
        <p class="first_white_text">Hello I'm</p>
        <p class="second_white_text">Adalkis Peña </p>
        <p class="third_white_text">Junior Full Stack Web Developer</p>
      </div>
    </div>
    <div class="green">
      <img class="me_img" src="@/assets/me.png" width="480px" height="479px" />
    </div>
  </div>
</template>
<style scoped>
.container_top {
  display: flex;
  background: linear-gradient(
    80deg,
    white 50.4%,
    white 50%,
    white calc(50% + 3px),
    #0db293 calc(50% + 3.5px)
  );
}
@media (max-width: 600px) {
  .container_top {
    background: linear-gradient(to bottom right, white 50%, #0db293 50%);
    height: 1650px;
  }

  .me_img {
    width: 700px;
    height: 700px;
    margin-top: 950px !important;
    margin-left: -220px !important;
  }
  .white_text.text-start {
    width: 500px;
  }
  .first_white_text {
    font-size: 60px !important;
  }
  .second_white_text {
    font-size: 80px !important;
  }
  .third_white_text {
    font-size: 40px !important;
  }
  .white {
    padding: 55px;
}
}

.white {
  width: 50%;
}
.white_text {
  padding: 255px 0 255px 0;
}
.first_white_text {
  color: #0db293;
  font-weight: bold;
  font-size: 25px;
  letter-spacing: 5px;
}
.second_white_text {
  font-family: "Montserrat Extra-Bold" !important;
  font-size: 40px;
  font-weight: bold;
}
.third_white_text {
  font-size: 16px;
  font-weight: bold;
}
.me_img {
  margin-top: 200px;
  margin-left: -100px;
}
</style>