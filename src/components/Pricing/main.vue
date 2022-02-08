<template>
<div class="container-pricing mb-20">
    <div class="text-center mb-20">
      <About/>
    </div>
    <div class="flex justify-around mt-10">
      <CardPrincipale/>
      <Card/>
      <CardPrincipale/>
    </div>
</div>
</template>

<script>
import About from "./About.vue";
import Card from "./Card.vue";
import CardPrincipale from "./CardPrincipale.vue";

export default {
  name: "Pricing",
  components: {
    About,
    Card,
    CardPrincipale
  },
}
</script> 

<style scoped>
.container-pricing{
/*width: 1777px; */
  height: 1155px;
  background: #252B42;
}
h2{
    /* H2 */
  font-family: Graphik;
  font-style: normal;
  font-weight: normal;
  font-size: 48px;
  line-height: 55px;
  /* identical to box height, or 115% */
  text-align: center;
  letter-spacing: 0.2px;

  /* Light text */
  color: #FFFFFF;
}
h4{
  /* H4 */
  font-family: Graphik;
  font-style: normal;
  font-weight: normal;
  font-size: 28px;
  line-height: 40px;
  /* or 143% */
  text-align: center;
  letter-spacing: 0.2px;

  /* Light text */
  color: #FFFFFF;

}

</style>