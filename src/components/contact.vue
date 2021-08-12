<template>
    <div class="container">
        <div class="contact" id="contact">
          <span>Full <span class="logo_text">Stack</span> </span>
        </div>
        <div class="contact_icons_container">
            <div class="contact_icons " id="linkedin">
                <a href="https://www.linkedin.com/in/adalkis-pe%C3%B1a-rosario-2679721b7/" target="_blank"> <i class="fab fa-linkedin"></i></a>

            </div>
            <div class="contact_icons">
                <a href="https://github.com/Adalkis?tab=repositories" target="_blank"><i class="fab fa-github"></i></a>
                 

            </div>
           
           
        </div>
        <p>adalkis2000@gmail.com</p>
    </div>
</template>

<script>
export default {
    
}
</script>

<style scoped>
@media (max-width:600px) {
    div#contact {
    font-size: 50px;
}
.contact_icons {
    width: 100px !important;
    height: 100px !important;
    border-radius: 50px !important;
    font-size: 50px !important;
}
p {
    font-size: 50px;
}

    
}
.contact{
  font-weight: bold;
  font-size: 18px;
}
.contact_icons_container{
    display: flex;
    justify-content: center;
}
.contact_icons {
    background: rgb(241, 239, 239);
    padding: 10px;
    font-size: 20px;
    border-radius: 25px;
    margin: 10px;
    width: 50px;
    height: 50px;
    
}
a{
    color: black !important;
}
</style>