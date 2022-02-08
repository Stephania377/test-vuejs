<template>
  <div class="test flex justify-around mb-30">
      <div class="w-2/3 couverture">
          <Couverture/>
      </div>
      <div class="w-1/3">
          <Subscribe/>
      </div>
  </div>
</template>

<script>
import Couverture from "./Couverture.vue";
import Subscribe from "./Subscribe.vue";

export default {
     name: "NewsLetters",
  components: {
      Couverture,
      Subscribe
  },
}
</script>

<style scoped>


.test{
    width:1200px;
    margin:auto;
    display: flex;
    flex-direction: row;
    align-items: flex-start;
    padding: 0px 50px;
    position: static;
    left: calc(50% - 1548.23px/2 - 0px);
    top: 3329.3px;

}

.primary{
    background: #2091F9;
}

.btn{
     font-family: Graphik;
    font-style: normal;
    font-weight: normal;
    font-size: 20px;
    line-height: 20px;
    /* identical to box height, or 100% */
    letter-spacing: 0.2px;

    /* Light text */
    color: #FFFFFF;
}

h2{
    /* H2 */
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
.tata{



/* Inside auto layout */
flex: none;
order: 4;
flex-grow: 0;
margin: 0px 0px;


/* left-container */

/* Auto layout */
display: flex;
flex-direction: row;
align-items: center;
padding: 0px;

position: static;
width: 854.23px;
height: 532px;
left: 50px;
top: 106px;


/* Inside auto layout */
flex: none;
order: 0;
align-self: flex-end;
flex-grow: 0;
margin: 0px 50px;


/* # screen content */

/* Auto layout */
display: flex;
flex-direction: column;
align-items: flex-end;
padding: 0px;

position: static;
width: 854.23px;
height: 514px;
left: 0px;
top: 9px;


/* Inside auto layout */
flex: none;
order: 0;
flex-grow: 0;
margin: 0px 0px;


/* undraw_newsletter_vovu */

position: static;
width: 677px;
height: 514px;
left: 177.23px;
top: 0px;


/* Inside auto layout */
flex: none;
order: 0;
flex-grow: 0;
margin: 47.4574px 0px;


/* Vector */

position: absolute;
left: 17.35%;
right: 9.75%;
top: 72.52%;
bottom: 0%;

background: #F5F5F5;


/* Vector */

position: absolute;
left: 79.42%;
right: 4.73%;
top: 32.81%;
bottom: 12.37%;

/* Primary */
background: #2091F9;


/* Vector */

position: absolute;
left: 79.42%;
right: 10.03%;
top: 32.81%;
bottom: 12.37%;

border: 2px solid #535461;


/* Vector */

position: absolute;
left: 77.77%;
right: 0.02%;
top: 67.16%;
bottom: 9.91%;

/* Primary */



/* Vector */

position: absolute;
left: 77.77%;
right: 0.02%;
top: 67.16%;
bottom: 9.91%;

background: #F5F5F5;
opacity: 0.2;


/* Vector */

position: absolute;
left: 77.77%;
right: 0.02%;
top: 67.27%;
bottom: 13.27%;

border: 2px solid #535461;


/* Vector */

position: absolute;
left: 0%;
right: 44.74%;
top: 0%;
bottom: 7.44%;

/* Primary */
background: #2091F9;
opacity: 0.2;


/* Group */

position: absolute;
left: 10.92%;
right: 66.78%;
top: 4.24%;
bottom: 6.93%;

opacity: 0.5;


/* Vector */

position: absolute;
left: 10.92%;
right: 66.78%;
top: 4.24%;
bottom: 6.93%;

background: linear-gradient(90deg, rgba(128, 128, 128, 0.25) 0.01%, rgba(128, 128, 128, 0.12) 53.97%, rgba(128, 128, 128, 0.1) 99.95%);
opacity: 0.5;


/* Vector */

position: absolute;
left: 24.81%;
right: 70.55%;
top: 72.66%;
bottom: 12.92%;

background: #5A5773;


/* Vector */

position: absolute;
left: 22.92%;
right: 70.03%;
top: 50.39%;
bottom: 25.15%;

background: #605D82;


/* Vector */

position: absolute;
left: 22.92%;
right: 70.9%;
top: 50.4%;
bottom: 25.15%;

background: #000000;
opacity: 0.1;


/* Vector */

position: absolute;
left: 20.64%;
right: 75.05%;
top: 79.99%;
bottom: 8.51%;

background: #5A5773;


/* Vector */

position: absolute;
left: 16.02%;
right: 75.54%;
top: 51.37%;
bottom: 18.51%;

background: #605D82;


/* Group */

position: absolute;
left: 16.02%;
right: 75.54%;
top: 51.37%;
bottom: 19.25%;

opacity: 0.1;


/* Vector */

position: absolute;
left: 22.43%;
right: 75.54%;
top: 53.85%;
bottom: 19.25%;

background: #000000;
opacity: 0.1;


/* Vector */

position: absolute;
left: 18.37%;
right: 81.6%;
top: 66.47%;
bottom: 33.39%;

background: #000000;
opacity: 0.1;


/* Vector */

position: absolute;
left: 16.02%;
right: 77.08%;
top: 51.37%;
bottom: 46.8%;

background: #000000;
opacity: 0.1;


/* Vector */

position: absolute;
left: 29.04%;
right: 67.74%;
top: 45.89%;
bottom: 47.75%;

background: #FAC3CA;


/* Vector */

position: absolute;
left: 17.33%;
right: 73.93%;
top: 13.73%;
bottom: 74.17%;

background: #FAC3CA;


/* Vector */

position: absolute;
left: 14.68%;
right: 70.45%;
top: 19.47%;
bottom: 44.23%;

background: #000000;
opacity: 0.1;


/* Vector */

position: absolute;
left: 14.68%;
right: 70.45%;
top: 19.29%;
bottom: 44.41%;

background: #E1E7EF;


/* Vector */

position: absolute;
left: 21.46%;
right: 75.52%;
top: 80.61%;
bottom: 16.83%;

background: #5A5773;


/* Vector */

position: absolute;
left: 26.04%;
right: 71.34%;
top: 73.72%;
bottom: 23.45%;

background: #5A5773;


/* Vector */

position: absolute;
left: 24.49%;
right: 67.16%;
top: 17.3%;
bottom: 52.35%;

background: #000000;
opacity: 0.1;


/* Vector */

position: absolute;
left: 24.49%;
right: 67.16%;
top: 17.13%;
bottom: 52.52%;

background: #67647E;


/* Vector */

position: absolute;
left: 24.49%;
right: 70.61%;
top: 20.31%;
bottom: 49.15%;

background: #000000;
opacity: 0.1;


/* Vector */

position: absolute;
left: 24.63%;
right: 70.47%;
top: 20.39%;
bottom: 49.59%;

background: #67647E;


/* Vector */

position: absolute;
left: 14.52%;
right: 76.49%;
top: 18.32%;
bottom: 47.42%;

background: #000000;
opacity: 0.1;


/* Vector */

position: absolute;
left: 13.94%;
right: 76.66%;
top: 17.87%;
bottom: 47.86%;

background: #67647E;


/* Vector */

position: absolute;
left: 11.34%;
right: 80.36%;
top: 16.33%;
bottom: 62.38%;

background: #000000;
opacity: 0.1;


/* Vector */

position: absolute;
left: 11.47%;
right: 80.23%;
top: 30.42%;
bottom: 62.56%;

background: #000000;
opacity: 0.1;


/* Vector */

position: absolute;
left: 18.49%;
right: 77.57%;
top: 29%;
bottom: 65.6%;

background: #FAC3CA;


/* Vector */

position: absolute;
left: 11.34%;
right: 80.36%;
top: 16.15%;
bottom: 62.56%;

background: #67647E;


/* Vector */

position: absolute;
left: 19.81%;
right: 75.81%;
top: 13.9%;
bottom: 82.48%;

background: #000000;
opacity: 0.1;


/* Vector */

position: absolute;
left: 18.77%;
right: 74.53%;
top: 8.51%;
bottom: 82.65%;

background: #FAC3CA;


/* Vector */

position: absolute;
left: 16.32%;
right: 74.65%;
top: 4.75%;
bottom: 84.81%;

background: #000000;
opacity: 0.1;


/* Vector */

position: absolute;
left: 16.25%;
right: 74.71%;
top: 4.66%;
bottom: 84.9%;

background: #4A4347;


/* Vector */

position: absolute;
left: 27.37%;
right: 72.14%;
top: 25.79%;
bottom: 63.81%;

background: #000000;
opacity: 0.1;


/* Vector */

position: absolute;
left: 15.38%;
right: 84.32%;
top: 27.91%;
bottom: 68.03%;

background: #000000;
opacity: 0.1;


/* Vector */

position: absolute;
left: 34.02%;
right: 65.67%;
top: 68.87%;
bottom: 30.71%;

background: #000000;


/* Group */

position: absolute;
left: 25.32%;
right: 17.67%;
top: 16.31%;
bottom: 10.09%;

opacity: 0.5;


/* Vector */

position: absolute;
left: 25.32%;
right: 17.67%;
top: 16.31%;
bottom: 10.09%;

background: linear-gradient(0deg, rgba(128, 128, 128, 0.25) -73955%, rgba(128, 128, 128, 0.12) -45024.5%, rgba(128, 128, 128, 0.1) -20380%);
opacity: 0.5;


/* Vector */

position: absolute;
left: 26.3%;
right: 18.71%;
top: 17.57%;
bottom: 11.4%;

background: #FFFFFF;


/* Vector */

position: absolute;
left: 28.28%;
right: 20.69%;
top: 20.12%;
bottom: 13.96%;

background: #E0E0E0;


/* Vector */

position: absolute;
left: 31.33%;
right: 36.49%;
top: 30.29%;
bottom: 15.72%;

/* Primary */
background: #2091F9;
transform: matrix(0.97, -0.25, 0.25, 0.97, 0, 0);


/* Vector */

position: absolute;
left: 37.86%;
right: 29.96%;
top: 27.46%;
bottom: 18.55%;

background: #F5F5F5;


/* Vector */

position: absolute;
left: 26.56%;
right: 45.94%;
top: 45.52%;
bottom: 11.33%;

background: #000000;
opacity: 0.05;


/* Vector */

position: absolute;
left: 26.36%;
right: 46.15%;
top: 45.52%;
bottom: 11.33%;

background: #FFFFFF;


/* Vector */

position: absolute;
left: 53.64%;
right: 18.86%;
top: 45.52%;
bottom: 11.33%;

background: #000000;
opacity: 0.05;


/* Vector */

position: absolute;
left: 53.85%;
right: 18.66%;
top: 45.52%;
bottom: 11.33%;

background: #FFFFFF;


/* Vector */

position: absolute;
left: 26.36%;
right: 18.66%;
top: 59.68%;
bottom: 12.02%;

background: #000000;
opacity: 0.05;


/* Vector */

position: absolute;
left: 26.36%;
right: 18.66%;
top: 60.36%;
bottom: 11.33%;

background: #FFFFFF;


/* Vector */

position: absolute;
left: 31.4%;
right: 67.06%;
top: 72.2%;
bottom: 8.06%;

border: 2px solid #535461;


/* Vector */

position: absolute;
left: 31.08%;
right: 66.84%;
top: 67.95%;
bottom: 27.72%;

background: #6C63FF;


/* Vector */

position: absolute;
left: 32.8%;
right: 64.97%;
top: 71.46%;
bottom: 24.74%;

background: #6C63FF;


/* Vector */

position: absolute;
left: 32.34%;
right: 64.58%;
top: 78.07%;
bottom: 19.12%;

background: #6C63FF;


/* Vector */

position: absolute;
left: 31.41%;
right: 65.79%;
top: 83.67%;
bottom: 13.24%;

background: #6C63FF;


/* Vector */

position: absolute;
left: 30.33%;
right: 67.06%;
top: 73.09%;
bottom: 23.52%;

background: #6C63FF;


/* Vector */

position: absolute;
left: 28.99%;
right: 68.01%;
top: 79.18%;
bottom: 18.06%;

background: #6C63FF;


/* Vector */

position: absolute;
left: 28.64%;
right: 68.48%;
top: 85.6%;
bottom: 11.23%;

background: #6C63FF;


/* Vector */

position: absolute;
left: 39.74%;
right: 47.35%;
top: 29.93%;
bottom: 68.7%;

background: #6C63FF;
opacity: 0.5;


/* Vector */

position: absolute;
left: 39.74%;
right: 32.35%;
top: 35.43%;
bottom: 63.2%;

background: #6C63FF;
opacity: 0.5;


/* Vector */

position: absolute;
left: 39.74%;
right: 32.35%;
top: 39%;
bottom: 59.63%;

background: #6C63FF;
opacity: 0.5;


/* Vector */

position: absolute;
left: 39.74%;
right: 32.35%;
top: 42.57%;
bottom: 56.06%;

background: #6C63FF;
opacity: 0.4;


/* Vector */

position: absolute;
left: 39.74%;
right: 32.35%;
top: 46.14%;
bottom: 52.48%;

background: #6C63FF;
opacity: 0.4;


/* Vector */

position: absolute;
left: 39.74%;
right: 44.33%;
top: 49.71%;
bottom: 48.91%;

background: #6C63FF;
opacity: 0.3;


/* Vector */

position: absolute;
left: 39.74%;
right: 38.5%;
top: 53.29%;
bottom: 45.34%;

background: #6C63FF;
opacity: 0.3;


/* right-container */

/* Auto layout */
display: flex;
flex-direction: column;
align-items: flex-start;
padding: 0px 63px;

position: static;
width: 544px;
height: 500px;
left: 954.23px;
top: 69px;


/* Inside auto layout */
flex: none;
order: 1;
align-self: center;
flex-grow: 0;
margin: 0px 50px;


/* padding top */

position: static;
width: 546px;
height: 106px;
left: -1px;
top: 0px;


/* Inside auto layout */
flex: none;
order: 0;
align-self: center;
flex-grow: 0;
margin: 15px 0px;


/* # text content */

/* Auto layout */
display: flex;
flex-direction: column;
align-items: flex-start;
padding: 0px;

position: static;
width: 324px;
height: 165px;
left: 63px;
top: 121px;


/* Inside auto layout */
flex: none;
order: 1;
align-self: flex-start;
flex-grow: 0;
margin: 15px 0px;


/* H3 */

/* Auto layout */
display: flex;
flex-direction: row;
align-items: center;
padding: 0px;

position: static;
width: 173px;
height: 28px;
left: 0px;
top: 0px;


/* Inside auto layout */
flex: none;
order: 0;
flex-grow: 0;
margin: 7px 0px;


/* At your fingertips */

position: static;
left: 0%;
right: 0%;
top: 0%;
bottom: 0%;

/* H3 */
font-family: Graphik;
font-style: normal;
font-weight: bold;
font-size: 20px;
line-height: 28px;
/* identical to box height, or 140% */
letter-spacing: 0.1px;

/* text */
color: #252B42;


/* Inside auto layout */
flex: none;
order: 0;
flex-grow: 0;
margin: 0px 0px;


/* H2 */

/* Auto layout */
display: flex;
flex-direction: row;
align-items: center;
padding: 10px 0px;

position: static;
width: 324px;
height: 130px;
left: 0px;
top: 35px;


/* Inside auto layout */
flex: none;
order: 1;
flex-grow: 0;
margin: 7px 0px;


/* Lightning fast prototyping */

position: static;
left: 0%;
right: 0%;
top: 7.69%;
bottom: 7.69%;




/* Inside auto layout */
flex: none;
order: 0;
flex-grow: 0;
margin: 0px 10px;


/* # Action content */

/* Auto layout */
display: flex;
flex-direction: column;
align-items: flex-start;
padding: 0px;

position: static;
width: 477px;
height: 199px;
left: 63px;
top: 301px;


/* Inside auto layout */
flex: none;
order: 2;
align-self: flex-start;
flex-grow: 0;
margin: 15px 0px;


/* @ desktop-newsletter  */

/* Auto layout */
display: flex;
flex-direction: column;
align-items: flex-start;
padding: 10px;

position: static;
width: 477px;
height: 199px;
left: 0px;
top: 0px;


/* Inside auto layout */
flex: none;
order: 0;
flex-grow: 0;
margin: 13px 0px;


/* H3 */

/* Auto layout */
display: flex;
flex-direction: row;
align-items: center;
padding: 0px;

position: static;
width: 276px;
height: 28px;
left: 10px;
top: 10px;


/* Inside auto layout */
flex: none;
order: 0;
align-self: flex-start;
flex-grow: 0;
margin: 0px 0px;


/* Subscribe to our Newsletter */

position: static;
left: 0%;
right: 0%;
top: 0%;
bottom: 0%;

/* H3 */
font-family: Graphik;
font-style: normal;
font-weight: bold;
font-size: 20px;
line-height: 28px;
/* identical to box height, or 140% */
letter-spacing: 0.1px;

/* text */
color: #252B42;


/* Inside auto layout */
flex: none;
order: 0;
flex-grow: 0;
margin: 0px 10px;


/* Text Paragraphe */

/* Auto layout */
display: flex;
flex-direction: row;
align-items: center;
padding: 0px;

position: static;
width: 301px;
height: 25px;
left: 10px;
top: 38px;


/* Inside auto layout */
flex: none;
order: 1;
align-self: flex-start;
flex-grow: 0;
margin: 0px 0px;


/* Available exclusivery on Figmaland */

position: static;
left: 0%;
right: 0%;
top: 0%;
bottom: 0%;

/* Paragraphe */
font-family: Graphik;
font-style: normal;
font-weight: normal;
font-size: 18px;
line-height: 25px;
/* identical to box height, or 139% */
letter-spacing: 0.2px;

/* second text */
color: #374754;


/* Inside auto layout */
flex: none;
order: 0;
flex-grow: 0;
margin: 0px 10px;


/* @ mailing input-2 */

/* Auto layout */
display: flex;
flex-direction: row;
align-items: center;
padding: 34px 0px;

position: static;
width: 457px;
height: 126px;
left: 10px;
top: 63px;


/* Inside auto layout */
flex: none;
order: 2;
align-self: flex-start;
flex-grow: 0;
margin: 0px 0px;


/* input */

/* Auto layout */
display: flex;
flex-direction: column;
align-items: flex-start;
padding: 19px 39px;

position: static;
left: 0%;
right: 40.26%;
top: 28.57%;
bottom: 28.57%;

background: #F4F4F4;
border: 1px solid #E8E8E8;
box-sizing: border-box;
border-radius: 39px;

/* Inside auto layout */
flex: none;
order: 0;
flex-grow: 0;
margin: 0px 12px;


/* Your Email */

position: static;
width: 68px;
height: 16px;
left: 39px;
top: 19px;

font-family: Roboto;
font-style: normal;
font-weight: normal;
font-size: 14px;
line-height: 16px;
/* identical to box height, or 114% */
letter-spacing: 0.1px;

/* Background */
color: #18171D;


/* Inside auto layout */
flex: none;
order: 0;
flex-grow: 0;
margin: 64px 0px;


/* master button */

/* Auto layout */
display: flex;
flex-direction: column;
align-items: center;
padding: 19px 38px;

position: static;
left: 62.36%;
right: 0%;
top: 26.98%;
bottom: 26.98%;

/* Primary */
background: #2091F9;
border-radius: 35px;

/* Inside auto layout */
flex: none;
order: 1;
flex-grow: 0;
margin: 0px 12px;


/* Text Button */

/* Auto layout */
display: flex;
flex-direction: row;
align-items: center;
padding: 0px;

position: static;
width: 96px;
height: 20px;
left: 38px;
top: 19px;


/* Inside auto layout */
flex: none;
order: 0;
flex-grow: 0;
margin: 10px 0px;


/* Subscribe */

position: static;
left: 0%;
right: 0%;
top: 0%;
bottom: 0%;

/* Button */



/* Inside auto layout */
flex: none;
order: 0;
flex-grow: 0;
margin: 0px 10px;

}
</style>