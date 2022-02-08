<template>
  <div class="flex-justify-center mb-10">
      <h2 class="mb-5">Parteners</h2>
      <h4>Most calendars are designed for teams. </h4>
      <h4>Slate is designed for freelancers.</h4>
  </div>
</template>

<script>
export default {
    name:'About'
}
</script>

<style scoped>
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
  /* text */
  color: #252B42;
}
h4{
  /* H4 */
font-family: Graphik;
font-style: normal;
font-weight: normal;
font-size: 27px; /* 28px */
line-height: 40px;
/* or 143% */
text-align: center;
letter-spacing: 0.2px;

/* second text */
color: #374754;

}
 .container-about{
/* Auto layout */
display: flex;
flex-direction: column;
align-items: center;
padding: 0px;
position: static;
width: 552px;
height: 222px;
 }
</style>