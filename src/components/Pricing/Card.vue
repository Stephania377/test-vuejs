<template>
 <div class="container-carrd shadow-lg rounded-2xl w-64 bg-white dark:bg-gray-800 p-4">
        <h3>STANDARD</h3>
        <h6>For the basics tailwind</h6>
    <div class="price grid grid-cols-2 mt-5 mb-10">
        <div><h1>10</h1> </div>
        <div><h3>$</h3> <h6>Per month </h6></div>
    </div>   
    <div class="element">
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
  name: 'Card',
}
</script>

<style scoped>
.liste{
    width: 255px;
    height : 240px;
    margin:auto;
}

.container-carrd{
    background: #2091F9;
    border: 1px solid #DEDEDE;
    box-sizing: border-box;
    box-shadow: 0px 13px 19px rgba(0, 0, 0, 0.07);
    border-radius: 10px;
    display: flex;
    flex-direction: column;
    align-items: center;
    padding: 83px 10px;

    position: static;
    width: 335px;
    height: 693px;
    left: 385px;
    top: 0px;

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

    /* Primary */
    color: #2091F9;
    /* Light text */
    background: #FFFFFF;
    border-radius: 35px;
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

    /* Light text */
    color: #FFFFFF;
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

    /* Light text */
    color: #FFFFFF;
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
    /* Light text */
    color: #FFFFFF;
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
    color: #ffffff;
}

.element{
    display: flex;
    text-align: center;
    padding: 10px;
}
</style>