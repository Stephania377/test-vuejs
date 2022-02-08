<template>
  <div class="footer flex justify-around p-52">
      <Theme />
      <Other />
    </div>
</template>
<script>
import Theme from "./Theme.vue";
import Other from "./Other.vue";


export default {
  name: "Footer",
  components: {
    Theme,
    Other,
  }
  
};
</script>

<style scoped>
.footer{
  width:1777px;
  height:567px;
  background: #252B42;
}




container-footer{
  /* content */

/* Auto layout */
display: flex;
flex-direction: row;
align-items: flex-start;
padding: 0px;

position: static;
width: 991px;
height: 267px;
left: 393px;
top: 150px;
}

</style>