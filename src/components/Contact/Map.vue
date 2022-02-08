<template>
    <div>
        <div class="header-map flex justify-center">
            <div class="text-center contain1">
                <span><i class="fa fa-map-marker-alt fa-2x" style="color:#2091F9"> </i></span>
                <h6> 63896 Spring St undefined Anchorage. Georgia 12473 United States </h6>
            </div>
            <div class=" text-center contain2">
                <span><i class="fa fa-mobile-alt fa-2x" style="color:#2091F9"> </i></span>
                <h6> (843) 555-0130 </h6>
            </div>
            <div class="text-center contain3">
                <span><i class="fa fa-envelope fa-2x" style="color:#2091F9"> </i></span>
                <h6> willie.jennings@example.com </h6>
            </div>
        </div>

        <div class="flex justify-center mb-10 mt-10 ">
            <img src="./Image/carte.png" alt="" class="map">
        </div>

        <div class="flex mt-5">
            <span class="mr-6"><i class="fab fa-twitter fa-2x" style="color:#2091F9"></i></span>
            <span class="mr-6"><i class="fab fa-facebook-square fa-2x" style="color:#2091F9"></i></span>
            <span class="mr-6"><i class="fab fa-linkedin fa-2x" style="color:#2091F9"></i></span>
        </div>
    </div>
</template>

<script>
export default {
    name: "Map",
}
</script>

<style scoped>
.map{
    /* Frame 21 */

/* Auto layout */
display: flex;
flex-direction: column;
align-items: flex-start;
padding: 10px;
position: static;
width: 516px;
height: 323.19px;
border-radius: 48px;

}
.bx-map{
    /* bx:bx-map */

position: static;
width: 26px;
height: 32px;
left: 143.5px;
top: 0px;

}
.primary{
    /* Primary */
background: #2091F9;
}

.contain1{
    flex-direction: row;
    align-items: center;
    padding: 10px;

    position: static;
    width: 313px;
    height: 66px;

}
.contain2{
    flex-direction: row;
    align-items: center;
    padding: 10px;
    position: static;
    width: 137px;
    height: 43px;


}
.contain3{
    flex-direction: row;
    align-items: center;
    padding: 10px;
    position: static;
    width: 245px;
    height: 43px;

}
h6{
    /* H5 */
font-family: Graphik;
font-style: normal;
font-weight: normal;
font-size: 16px;
line-height: 23px;
/* or 144% */
text-align: center;
letter-spacing: 0.1px;

/* second text */
color: #374754;
}
.header-map{

/* Auto layout */
display: flex;
flex-direction: row;
align-items: flex-start;
padding: 0px;

position: static;
width: 725px;
height: 108px;


}

</style>