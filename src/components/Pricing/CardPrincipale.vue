<template>
  
<div class="container-card shadow-lg rounded-2xl w-64 bg-white dark:bg-gray-800 p-4 mt-10">
        <h3>FREE</h3>
        <h6>For the basics tailwind</h6>
    <div class="price grid grid-cols-2 mt-5 mb-10">
        <div><h1>0</h1> </div>
        <div><h3>$</h3> <h6>Per month</h6></div>
    </div>   
    <div class="element mt-5">
        <div class="liste ">
            <p class="link"> Price Feature</p>
            <p class="link"> Price Feature</p>
            <p class="link"> Price Feature</p>
            <p class="link"> Price Feature</p>
        </div>  
    </div>  
    <button type="button" class="w-56 m-auto px-3 py-3 text-sm shadow border text-white bg-white hover:bg-blue-400 hover:text-white dark:hover-text-gray-900 dark:hover:bg-gray-100 ">
        Order now
    </button>
    
    
</div>

</template>

<script>
export default {
  name: 'CardPrincipale',
}
</script>

<style scoped>
.price{
    width:153px;
    height:61px;

}
.liste{
    width: 255px;
    height : 240px;
    margin:auto;
}
button{
        /* Button */
    font-family: Graphik;
    font-style: normal;
    font-weight: normal;
    font-size: 20px;
    line-height: 20px;
    /* identical to box height, or 100% */
    letter-spacing: 0.2px;
    /* Light text */
    color: #FFFFFF;
    background: #2091F9;
    border-radius: 35px;
}
.container-card{
    /* Auto layout */
    display: flex;
    flex-direction: column;
    align-items: center;
    padding: 40px;

    position: static;
    width: 335px;
    height: 607px;
    left: 0px;
    top: 43px;

    /* light background */
    background: #FFFFFF;
    border: 1px solid #DEDEDE;
    box-sizing: border-box;
    box-shadow: 0px 13px 19px rgba(0, 0, 0, 0.07);
    border-radius: 10px;
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

    /* text */
    color: #252B42;

}

h6{
    /* H5 */
    font-family: Graphik;
    font-style: normal;
    font-weight: normal;
    font-size: 16px;
    line-height: 23px;
    /* or 144% */
    
    letter-spacing: 0.1px;

    /* second text */
    color: #5f5f5f;
    
}

h1{
        /* H1 */
    font-family: Graphik;
    font-style: normal;
    font-weight: bold;
    font-size: 74px;
    line-height: 84px;
    /* identical to box height, or 114% */
    letter-spacing: 0.2px;

    /* text */
    color: #252B42;
}

.link{
/* Link */
font-family: Graphik;
font-style: normal;
font-weight: normal;
font-size: 15px;
line-height: 28px;
/* identical to box height, or 187% */
letter-spacing: 0.2px;
margin-bottom:15px;
/* text */
color: #252B42;

}
.element{
    display: flex;
    text-align: center;
    padding: 10px;
}
</style>