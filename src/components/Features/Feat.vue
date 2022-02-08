<template>
  <div class="container-feat">
      <div class="grid grid-cols-3">
        <div class="text-center mr-10">
            <div class="mb-2">
               <span><i class="fas fa-pencil-ruler fa-2x" style="color: #2492f8"></i></span> 
            </div>
            <div class="mb-4">
                <h3>OpenType Features Variable fonts</h3> 
            </div>
            <div class="parag">
                Slate helps you see how many nore days you need to work to reach your financial goal 
            </div>
        </div>
        <div class="text-center mr-10">
            <div class="mb-2">
                <span><i class="fas fa-crop-alt fa-2x" style="color: #2492f8"></i></span> 
            </div>
            <div class="mb-4">
                <h3>Design with real data</h3> 
            </div>
            <div class="parag">
                Slate helps you see how many nore days you need to work to reach your financial goal 
            </div>
        </div>
        <div class="text-center mr-10">
            <div class="mb-2">
                <span><i class="far fa-clone fa-2x" style="color: #2492f8"></i></span> 
            </div>
            <div class="mb-4">
                <h3> Fastest way to take action</h3> 
            </div>
            <div class="parag">
               Slate helps you see how many nore days you need to work to reach your financial goal 
            </div>
        </div>
   
      </div>
      


  </div>
</template>

<script>
export default {
    name: "Feat"
}
</script>

<style scoped>

.container-feat{
    display: flex;
    flex-direction: column;
    align-items: flex-start;
    padding: 0px;

    position: static;
    width: 869px;
   height: 257px; 
    left: calc(50% - 869px/2);
    bottom: 842.3px;

}
h3{
    font-family: Graphik;
    font-style: normal;
    font-weight: bold;
    font-size: 20px;
    line-height: 28px;
    /* or 140% */
    text-align: center;
    letter-spacing: 0.1px;

    /* text */
    color: #252B42;
}
.parag{
    font-family: Graphik;
font-style: normal;
font-weight: normal;
font-size: 18px;
line-height: 25px;
/* or 139% */
text-align: center;
letter-spacing: 0.2px;

/* second text */
color: #374754;
}

</style>