<template>
  <div class="cont1">
    <div class="cont2">
      <Menu />
      <div class="title">
        <Title />
      </div>
    <div class="grid grid-cols-2">
      <div class="triangle"></div>
      <div class="triangle2"> </div>
    </div>
  </div>
  </div>


</template>

<script>
import Menu from "./Menu.vue";
import Title from "./Title.vue";


export default {
  name: "Footer",
  components: {
    Menu,
    Title
  },
};
//backdrop-filter: opacity(50%);
</script>

<style scoped>
  .title{
    text-align: center;
    /*margin-top: 115px;  */
    margin-top:70px;
  }

  .triangle{
    width:0%;
    border-bottom:solid 130px white;
    border-right:solid 700px transparent;
}

   .triangle2{
    width:0;
    border-bottom:solid 130px white;
    border-left:solid 700px transparent;
}

  .cont1{
    background-image: url('Image/machine.jpg');
    
  } 
  .cont2{
    /* background-color: rgb(30, 43, 50, 0.4); */
    background-color: rgb(0, 0, 0, 0.6); 
  }

</style>