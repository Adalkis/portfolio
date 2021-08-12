<template>
  <div class="container">
      <div class="icons">
        <div class="zoom">
          <i :class="icon_name">{{icon_text}}</i>
          <p class="icons_text">{{text}}</p>
        </div>
      </div>
    </div>
</template>

<script>
export default {
  name: "containerIcon",
  props: {
    icon_name: {
      type: String,
      required:true,
    },
    text: {
      type: String,
      required:true,
    },
    icon_text:{
        type:String,
        
    }
  },
};
</script>

<style scoped>

.icons {
  display: flex;
  justify-content: space-evenly;
}
i {
  font-size: 40px;
  background: #0db293;
  color: white;
  padding: 16px 25px 16px 25px;
  border-top-left-radius: 20px;
  border-top-right-radius: 20px;
  border-bottom-left-radius: 20px;
  width: 85px;
}
._icons {
  background: #0db293;
  padding: 50px 80px 50px 80px;
  border-radius: 20px;
  width: 280px;
  height: 200px;
}
.zoom:hover{
  transform: scale(1.2);
}
@media (max-width:600px){
  .icons_text{
    font-size:30px !important;
  }
}
</style>