<template>
  <div class="container-titre flex justify-center items-center h-screen" >
    <h1 class="title font-bold">
      The best products start with figma
    </h1>
    <h4 class="subtitle">
     Most calendars are designed for teams. Slate is designed for freelancers.
    </h4>
    <div class="mt-10">
      <button type="submit" class="text-white hover:bg-blue-500 focus:ring-4 focus:ring-blue-300 font-medium rounded-lg text-sm w-full sm:w-auto px-5 py-2.5 text-center dark:bg-blue-600 dark:hover:bg-blue-700 dark:focus:ring-blue-800">Try for free</button>
    </div>
  </div>
</template>

<script>
export default {
    name:'Title'
}
</script>

<style scoped>
.container-titre{ 
  display: flex;
  flex-direction: column;
  align-items: center;
  padding: 20px;

  position: static;
  width: 826px;
  height: 335px;
  margin-top:80px;
  margin:auto;
}
  .title{
    font-family: Graphik;
    font-style: normal;
    font-weight: bold;
    font-size: 74px;
    line-height: 84px;

    text-align: center;
    letter-spacing: 0.2px;

    /* Light text */
    color: #FFFFFF;
  }
  .subtitle{
    font-family: Graphik;
    font-style: normal;
    font-weight: normal;
    font-size: 28px;
    line-height: 40px;
    text-align: center;
    letter-spacing: 0.2px;
    color: #FFFFFF;
    margin-top:20px;
  }
  button{
    width: 236px;
    height: 52px;
    font-family: Graphik;
    font-style: normal;
    font-weight: normal;
    font-size: 20px;
    line-height: 20px;
    text-align: center;
    letter-spacing: 0.2px;
    color: #FFFFFF;
    flex: none;
    order: 0;
    flex-grow: 0;
    margin-top: 40px;
    background: #2091F9;
    border-radius: 35px;
  }
 
</style>