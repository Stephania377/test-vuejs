<template>
  <div class="container-partenaire text-center mb-20 mt-20">
    <div class="mb-10">
        <About/>
    </div>
    <div class="flex justify-center mb-5">
        <Society/>
        
    </div>
      <button type="submit" class="text-white hover:bg-blue-500 focus:ring-4 focus:ring-blue-300 font-medium rounded-lg text-sm w-full sm:w-auto px-5 py-2.5 text-center dark:bg-blue-600 dark:hover:bg-blue-700 dark:focus:ring-blue-800">Try for free</button>

  </div>
</template>

<script>
import About from "./About.vue";
import Society from "./Society.vue";
export default {
  name: "Parteners",
  components: {
    About,
    Society
  },
};
</script>

<style scoped>
.container-partenaire{
  width:1200px;

}
.container-society{
  margin:auto;
}
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
button{
position: static;
width: 236px;
height: 60px;
/* Primary */
background: #2091F9;
border-radius: 35px;
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
</style>