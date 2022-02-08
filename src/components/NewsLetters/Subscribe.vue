<template>
  <div class="right mt-20 ml-5" >
      <div>
        <h3> At your fingertips</h3>
      </div>
      <div class="mb-5">
          <h2>Lightning fast prototyping </h2>
      </div>
      <div>
          <h3>Subscribe to our newsletter </h3>
      </div>
      <div class="mb-5">
          <p class="paragraphe">Available exclusively on Figmaland</p>
      </div>
      <div class="flex">
            <div class="mr-3">
                <input type="password" id="password" class="input bg-gray-50 border border-gray-300 text-gray-900 text-sm rounded-lg focus:ring-blue-500 focus:border-blue-500 block w-full p-2.5 dark:bg-gray-700 dark:border-gray-600 dark:placeholder-gray-400 dark:text-white dark:focus:ring-blue-500 dark:focus:border-blue-500" placeholder="your name" required>
            </div>
            <div>
                <button type="submit" class="button text-white hover:bg-blue-500 focus:ring-4 focus:ring-blue-300 font-medium rounded-lg text-sm w-full sm:w-auto px-5 py-2.5 text-center dark:bg-blue-600 dark:hover:bg-blue-700 dark:focus:ring-blue-800">Subscribe</button>
            </div>
      </div>
  </div>
</template>

<script>
export default {
    name:'Subscribe'
}
</script>

<style scoped>
h3{
    font-family: Graphik;
    font-style: normal;
    font-weight: bold;
    font-size: 20px;
    line-height: 28px;
    letter-spacing: 0.1px;
    color: #252B42;
}
h2{
    font-family: Graphik;
    font-style: normal;
    font-weight: normal;
    font-size: 48px;
    line-height: 55px;
    /* or 115% */
    letter-spacing: 0.2px;

    /* text */
    color: #252B42;
}
.paragraphe{
    font-family: Graphik;
    font-style: normal;
    font-weight: normal;
    font-size: 18px;
    line-height: 25px;
    letter-spacing: 0.2px;

    /* second text */
    color: #374754;
}
.primary{
    /* Primary */
    background: #2091F9;
    border-radius: 35px;

}
.button{
   /* master button */


/* Primary */
background: #2091F9;
border-radius: 45px;


/* Text Button */





/* Button */
font-family: Graphik;
font-style: normal;
font-weight: normal;
font-size: 20px;


/* Light text */
color: #FFFFFF;


}
.input{
    position: static;
    left: 39px;
    top: 19px;
    border-radius:39px;
    font-family: Roboto;
    font-style: normal;
    font-weight: normal;
    font-size: 14px;
    line-height: 16px;
    letter-spacing: 0.1px;
    color: #18171D;
}
    
</style>