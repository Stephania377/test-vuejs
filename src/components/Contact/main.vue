<template>
    <div>
        <div class="text-center mb-20">
            <About/>
        </div>
        <div class="container-form flex justify-around">

                <Formulaire/>

                <Map/>

        </div>
    </div>
</template>

<script>

import About from "./About.vue";
import Map from "./Map.vue";
import Formulaire from "./Formulaire.vue";

export default {
    name: "Contact",
    components: {
      About,  
      Formulaire,  
      Map  
    },
}
</script>

<style scoped>

.map{
    /* border:1px solid black; */
    width:100%;
    height: 200px;
}
.container-form{
    /* Auto layout */
 
    margin:auto;

    position: static;
    width: 1228px;
  /*  height: 669px; */
    
}
</style>