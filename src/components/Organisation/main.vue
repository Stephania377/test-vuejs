<template>
  <div class="container-organize mb-20">
    <div class="grid grid-cols-2">
       <div> <Description /> </div>
       <div class="couv"> <Couverture /></div>
    </div>
  </div>
</template>

<script>
import Couverture from "./Couverture.vue";
import Description from "./Description.vue";
export default {
  name: "Organisation",
  components: {
    Couverture,
    Description,
  },
};
</script>

<style scoped >
.couverture {
  width: 300px;
  height: 150px;
  border: 1px solid black;
}
.container-organize{
  display: flex;
  flex-direction: row;
  align-items: center;
  padding: 43px 0px;
  position: static;
  width: 1243.3px;
  height: 472px;
  left: calc(50% - 1243.3px/2 + 0px);
  top: 226px;
  margin:auto;
}


</style>