<template>
  <div class="text-center mb-20 mt-10">
      <h2>Testimonials</h2>
    <div class="ibm">
      <img src="./Image/ibm.png" alt="" class="logo">
      <div class="parag mt-1 mb-7">
       <h4> Most calendars are designed for teams. Slate is designed for freelancers who want a simple way to  plan their schedule </h4>
      </div>

      <div class="container-avatar mt-10 mb-10">
          <img src="./Image/black.png" alt="" class="avatar">
        <div>
          <div>
            <h6> Organize Across </h6>
          </div>
          <div class="link">
            UI Designer
          </div>
        </div>
      </div>
    </div>
    
      <button type="submit" class="text-white hover:bg-blue-400 focus:ring-4 focus:ring-blue-300 font-medium rounded-lg text-sm w-full sm:w-auto px-5 py-2.5 text-center dark:bg-blue-600 dark:hover:bg-blue-700 dark:focus:ring-blue-800">More testimonials</button>
       
  </div>
</template>

<script>
export default {
    name: "Testimonials",
}
</script>

<style scoped>
  .container-avatar{
/* Auto layout */
display: flex;
flex-direction: row;
align-items: center;
padding: 0px;
position: static;
width: 186px;
height: 55px;
margin:auto;



  }
  .avatari{
    width: 50px;
    height: 50px;
    border-radius: 100%;
    border:1px solid black;

  }
  .parag{
    height:100px;
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
  /* text */
  color: #252B42;
  margin-bottom: 30px;
}
.ibm{

  width: 987px;
  height: 315px;
  margin:auto;

}

.lien{
  /* Link */
  font-family: Graphik;
  font-style: normal;
  font-weight: normal;
  font-size: 15px;
  line-height: 28px;
  /* identical to box height, or 187% */
  letter-spacing: 0.2px;

  /* text */
  color: #252B42;
}
.logo{
  align-items: center;
  padding: 0px;
  /* log ibm */
  width: 149.85px;
  height: 60px;
  margin:auto;
}
.vecteur{

position: absolute;
left: 0%;
right: 0%;
top: 0%;
bottom: 0.1%;

background: #1F70C1;


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

  /* second text */
  color: #374754;
}

 .avatar{
   position: static;
    width: 50px;
    height: 50px;
  border-radius:100%;

 }
  h6{
    /* H5 */
    font-family: Graphik;
    font-style: normal;
    font-weight: normal;
    font-size: 16px;
    line-height: 23px;
    /* identical to box height, or 144% */
    letter-spacing: 0.1px;

    /* second text */
    color: #374754;

  }
  button{
    padding: 0px;
    position: static;
    width: 276px;
    height: 60px;
    left: 581.5px;
    top: 650px;
    /* Primary */
    background: #2091F9;
    border-radius: 35px;
    /* Inside auto layout */
    flex: none;
    order: 0;
    flex-grow: 0;
    margin: 0px 0px;
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

</style>