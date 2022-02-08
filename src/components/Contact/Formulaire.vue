<template>
    <div class="formu">
        <div class="text-center mb-10 mt-10">
            <h3>Contact us</h3>
        </div>
        <div class="flex justify-center">
        <form >
            <div class="mb-6">
                <input type="password" id="password" class="text bg-gray-50 border border-gray-300 text-gray-900 text-sm rounded-lg focus:ring-blue-500 focus:border-blue-500 block w-full p-2.5 dark:bg-gray-700 dark:border-gray-600 dark:placeholder-gray-400 dark:text-white dark:focus:ring-blue-500 dark:focus:border-blue-500" placeholder="Your name" required>
            </div>
            <div class="mb-6">
                <input type="email" id="email" class="text bg-gray-50 border border-gray-300 text-gray-900 text-sm rounded-lg focus:ring-blue-500 focus:border-blue-500 block w-full p-2.5 dark:bg-gray-700 dark:border-gray-600 dark:placeholder-gray-400 dark:text-white dark:focus:ring-blue-500 dark:focus:border-blue-500" placeholder="Your email" required>
            </div>

             <div class="mb-6">
                <input type="text" id="message" class="message bg-gray-50 border border-gray-300 text-gray-900 text-sm rounded-lg focus:ring-blue-500 focus:border-blue-500 block w-full p-2.5 dark:bg-gray-700 dark:border-gray-600 dark:placeholder-gray-400 dark:text-white dark:focus:ring-blue-500 dark:focus:border-blue-500" placeholder="Your message" required>
            </div>
            <button type="submit" class="hover:bg-blue-400 focus:ring-4 focus:ring-blue-300 font-medium rounded-lg text-sm w-full sm:w-auto px-5 py-2.5 text-center dark:bg-blue-600 dark:hover:bg-blue-700 dark:focus:ring-blue-800">Send</button>
        </form>
        </div>
    </div>
</template>

<script>
export default {
    name: 'Formulaire',
}
</script>

<style scoped>
    .formu{
        flex-direction: column;
        align-items: flex-start;
        padding: 0px;

        position: static;
        width: 453px;
        height: 669px;
        left: 0px;
        top: 0px;
        background: #FFFFFF;
        border: 1px solid #DDDDDD;
        box-sizing: border-box;
        /* SHADOW */
        box-shadow: 0px 13px 19px rgba(0, 0, 0, 0.07);
        border-radius: 20px;
        
    }
    .auto{
        /* Auto layout */
        display: flex;
        flex-direction: row;
        align-items: center;
        padding: 0px;

        position: static;
        width: 110px;
        height: 28px;
        left: 171.5px;
        top: 52px;
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
        color: #252B42;
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
        /* # Action content */
        /* Auto layout */
display: flex;
flex-direction: column;
align-items: center;
padding: 18px 38px;

position: static;
width: 145px;
height: 56px;
left: 50px;
top: 561px;

}
  input.text{

        position: static;
        width: 353px;


        background: #F5F5F5;
        border: 1px solid #E8E8E8;
        box-sizing: border-box;
        border-radius: 39px;

        font-family: Roboto;
        font-style: normal;
        font-weight: normal;
        font-size: 15px;
        line-height: 16px;
        /* identical to box height, or 107% */
        letter-spacing: 0.1px;
        /* Background */
        color: #18171D;
    }
    input.message{


        position: static;
        width: 353px;
        height: 193px;
        background: #F5F5F5;
        border: 1px solid #E8E8E8;
        box-sizing: border-box;
        font-family: Roboto;
        font-style: normal;
        font-weight: normal;
        font-size: 15px;
        line-height: 16px;
        /* identical to box height, or 107% */
        letter-spacing: 0.1px;

        /* Background */
        color: #18171D;

}

</style>