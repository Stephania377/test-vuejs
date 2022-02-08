<template>
    <div class="grid grid-cols-3 gauche">
      <div>
        <h3> Pages </h3>
        <p class="link"> Home </p>
        <p class="link"> Product </p>
        <p class="link"> Pricing </p>
        <p class="link"> About </p>
        <p class="link">  Contact </p>
      </div>
      <div>
        <h3> Tomophy </h3>
        <p class="link"> Eleanor </p>
        <p class="link"> Ted </p>
        <p class="link"> Annette </p>
        <p class="link"> Ted </p>
        <p class="link"> Jennie </p>
      </div>
      <div>
        <h3> Jane Black </h3>
        <p class="link"> Philippe </p>
        <p class="link"> Product </p>
        <p class="link"> Collen </p>
        <p class="link"> Marvin </p>
        <p class="link"> Bruce </p>
      </div>
    </div>
</template>

<script>
export default {
    name: 'Theme',
    props:['element']
}
</script>

<style scoped>
h3{
  /* H3 */
font-family: Graphik;
font-style: normal;
font-weight: bold;
font-size: 20px;
line-height: 28px;
/* identical to box height, or 140% */
letter-spacing: 0.1px;

/* Light text */
color: #FFFFFF;

}
.link{
/* Link */
font-family: Graphik;
font-style: normal;
font-weight: normal;
font-size: 15px;
line-height: 28px;
/* identical to box height, or 187% */
letter-spacing: 0.2px;

/* Light text */
color: #FFFFFF;

}
.gauche{
    /* Auto layout 
  display: flex;
  flex-direction: row;
  align-items: center;
  padding: 0px;
  */

  position: static;
  width: 582px;
  height: 267px;
  left: calc(50% - 582px/2 - 204.5px);
  top: calc(50% - 267px/2);

}
</style>