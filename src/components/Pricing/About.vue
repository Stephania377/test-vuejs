<template>
  <div class="pricing">
    <div class="mt-10 mb-5" >
      <h2>Pricing</h2>
    </div>
    <div class="mb-10">
     <h4> 
     Most calendars are designed for teams. Slate is designed for freelancers.
      </h4>
    </div>
  </div>
</template>

<script>
export default {
  name: 'About'
}
</script>

<style scoped>
.pricing{
  /* Auto layout */
  display: flex;
  flex-direction: column;
  align-items: center;
  padding: 0px;
 margin:auto;
  position: static;
  width: 552px;
  height: 182px;

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