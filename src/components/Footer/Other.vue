<template>
    <div class="container-other">
        <div>
           <p class="link"><i class="fa fa-map-marker-alt fa-2x" style="color:white"> </i> 7480 Hill Mockingbird undefined </p>
        </div>
         <div>
            <p class="link"><span><i class="fa fa-mobile-alt fa-2x" style="color:white"> </i></span> (239) 555-0108 </p>
        </div>
         <div class="flex mt-5">
            <span class="mr-5"><i class="fab fa-twitter fa-2x" style="color:white"></i></span>
            <span class="mr-5"><i class="fab fa-facebook-square fa-2x" style="color:white"></i></span>
            <span class="mr-5"><i class="fab fa-linkedin fa-2x" style="color:white"></i></span>
        </div>
    </div>
</template>

<script>
export default {
    name: 'Other',
}
</script>

<style scoped>
.link{
    /* Link */
font-family: Roboto;
font-style: normal;
font-weight: normal;
font-size: 15px;
line-height: 27px;
/* identical to box height, or 180% */
letter-spacing: 0.2px;

/* Light text */
color: #FFFFFF;

}
.container-other{
    /* row */

/* Auto layout */
display: flex;
flex-direction: column;
align-items: flex-start;
padding: 0px;

position: static;
width: 284px;
height: 193.99px;
left: 707px;
top: 0px;
}
</style>