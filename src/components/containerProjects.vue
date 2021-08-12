<template>
  <div class="container">
    <div class="card_container">
      <b-card>
        <b-card-body class="card_body">
          <p class="title">
            {{ title }}
          </p>
          <div class="container_sub">
               <p class="subtitle">
            {{ subtitle }}
          </p>

          </div>
         
          <div class="container_link">
            <div class="link mt-5">
              <a :href="link">GitHub repo</a>
            </div>
          </div>
        </b-card-body>
      </b-card>
    </div>
  </div>
</template>

<script>
export default {
  name: "containerProjects",
  props: {
    title: {
      type: String,
    },
    subtitle: {
      type: String,
    },
    link: {
      type: String,
    },
  },
};
</script>

<style scoped>
@media (max-width:600px){
  .card {
    width: 810px !important;
   
      margin-top: -290px;
    height: 900px !important;
    border-radius: 40px;

}
a {
    font-size: 40px !important;
}
.link {
    width: 300px !important;
    padding: 20px !important;
}
.card_body {
    margin-top: 240px;
}
p.title {
    font-size: 50px !important;
}
p.subtitle {
    font-size: 40px !important;
}
.card_container {
    display: flex;
    justify-content: center !important;
}
img#music {
    position: relative;
}

}
.card {
  position: unset;
  height: 220px;
  width: 1135px;
  background: white;
  margin-right: -3px;
  border-color: #0db293;
  border-width: 5px;
  
}
.card_container {
  display: flex;
  justify-content: flex-end;
}
.title {
  font-size: 25px;
  font-weight: bold;
}
.subtitle {
  font-size: 18px;
    width: 800px;

}
.link {
  background: #0db293;
  width: 120px;
  border-radius: 5px;
  padding: 3px 10px 3px 10px;
  
  
}

.container_link {
  display: flex;
  justify-content: center;
}
a {
    text-decoration: none;
    color: black;
    font-size: 18px;
}
.container_sub{
    display: flex;
    justify-content: center;
}
</style>