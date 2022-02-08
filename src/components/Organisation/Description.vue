<template>
        <h2>Fastest way to organized</h2>
         <h4>Most calendars are designed for teams. Slate is designed for freelancers.</h4>
      <div class="mt-10">
            <button type="submit" class="primary text-white hover:bg-blue-500 focus:ring-4 focus:ring-blue-300 font-medium rounded-lg text-sm w-full sm:w-auto px-5 py-2.5 text-center dark:bg-blue-600 dark:hover:bg-blue-700 dark:focus:ring-blue-800">Try to free</button>
        </div>

</template>

<script>
export default {
    name:'Description'
}
</script>

<style scoped>


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

h4{
  font-family: Graphik;
font-style: normal;
font-weight: normal;
font-size: 25px;
line-height: 40px;
/* or 143% */
letter-spacing: 0.2px;

/* second text */
color: #374754;

}

.primary{
  background: #2091F9;
  border: 1px solid #2091F9;
  box-sizing: border-box;
  border-radius: 35px;
  width: 236px;
  height: 60px;
  font-family: Graphik;
  font-style: normal;
  font-weight: bold;
  font-size: 20px;
  line-height: 28px;
  /* identical to box height, or 140% */
  letter-spacing: 0.1px;
}

.screen{
  /* Screen background */
  position: absolute;
  left: 9.03%;
  right: 9.37%;
  top: 0%;
  bottom: 1.81%;

  background: #000000;
  border: 5.39668px solid #9FA2A5;
  box-sizing: border-box;
  border-radius: 16.19px 16.19px 0px 0px;

}

.base{
  /* Base */
  position: absolute;
  left: 0%;
  right: 0%;
  top: 94.22%;
  bottom: 2.08%;
  background: #D8D8D8;
}

.base-btm{
  /* Base Bottom */
  position: absolute;
  left: 0%;
  right: 0%;
  top: 97.92%;
  bottom: 0%;
  background: #9FA2A5;
}

.grip{
  /* grip */
  position: absolute;
  left: 42.92%;
  right: 43.71%;
  top: 94.22%;
  bottom: 3.56%;
  background: #9FA2A5;
}

.screen-mask{ 
/* SCREEN MASK */
  position: absolute;
  left: 11.28%;
  right: 11.63%;
  top: 4.03%;
  bottom: 9.81%;
  /* background: url(Account Activity.png); */
}

</style>