<template>
    
 <Navbar />
    <div class="max-w-screen-2xl mx-auto flex flex-col mt-16">
        <div class="flex mx-auto gap-32">
            <div class="w-1/4">
                <LaTuaCard />
            </div>

            <div class="w-full my-12 rounded-3xl text-xl">
                <h1 class="text-[#e72b6f] text-4xl gap-3 font-semibold mb-4">I tuoi dati</h1>
                
                <div class="bg-[#f7f7f7] w-full rounded-3xl">
                    <div class="grid gap-6 mb-5 md:grid-cols-2 p-8 form-floating">
                        <div class="relative z-0 text-gray-700 w-full mb-6 group bg-white">
                            <input type="text" name="floating_name" id="floating_name" class="bg-gray-50 block p-4 text-sm rounded-lg w-full bg-transparent border dark:bg-gray-50 text-gray-800 dark:placeholder-gray-50 dark:text-white peer" placeholder=" " required />
                            <label for="floating_name" class="peer-focus:font-medium absolute text-sm text-gray-500 dark:text-gray-400 duration-300 transform -translate-y-6 scale-75 top-3 -z-10 origin-[0] peer-focus:start-0 rtl:peer-focus:translate-x-1/4 rtl:peer-focus:left-auto px-3 peer-placeholder-shown:scale-100 peer-placeholder-shown:translate-y-0 peer-focus:scale-x-75 peer-focus:-translate-y-2">Nome*</label>
                        </div>

                        <div class="relative z-0 text-gray-700 w-full mb-6 group bg-white">
                            <input type="text" name="floating_cognome" id="floating_cognome" class="bg-gray-50 block p-4 text-sm rounded-lg w-full bg-transparent border dark:bg-gray-50 text-gray-700 dark:placeholder-gray-50 dark:text-white peer" placeholder=" " required />
                            <label for="floating_cognome" class="peer-focus:font-medium absolute text-sm text-gray-500 dark:text-gray-400 duration-300 transform -translate-y-6 scale-75 top-3 -z-10 origin-[0] peer-focus:start-0 rtl:peer-focus:translate-x-1/4 rtl:peer-focus:left-auto px-3 peer-placeholder-shown:scale-100 peer-placeholder-shown:translate-y-0 peer-focus:scale-x-75 peer-focus:-translate-y-3">Cognome*</label>
                        </div>




                        <div class="relative z-0 w-full mb-6 group bg-white">
    <input type="Date" name="floating_data" id="floating_data" class="bg-gray-50 block py-3 px-0 text-sm rounded-lg w-full p-4 bg-transparent border dark:bg-gray-50 text-gray-700 dark:placeholder-gray-50 dark:text-white peer" placeholder=" " required />
    <label for="floating_data" class="peer-focus:font-medium absolute text-sm text-gray-500 dark:text-gray-400 duration-300 transform -translate-y-4 scale-75 top-3 -z-10 origin-[0] peer-focus:start-0 rtl:peer-focus:translate-x-1/4 rtl:peer-focus:left-auto px-3 peer-placeholder-shown:scale-100 peer-placeholder-shown:translate-y-0 peer-focus:scale-x-75 peer-focus:-translate-y-1">Data di nascita*</label>
</div>

  <div class="relative z-0 w-full mb-6 group bg-white">
                            <select name="floating_genere" id="floating_genere" class="bg-gray-50 block py-3 px-4 text-sm rounded-lg w-full bg-transparent border dark:bg-gray-50 text-gray-700 dark:placeholder-gray-50 dark:text-white peer" placeholder=" " required >
                                <option>Femmina</option>
                                <option>Uomo</option>
                            </select>
                            <label for="floating_genere" class="peer-focus:font-medium absolute text-sm text-gray-500 dark:text-gray-400 duration-300 transform -translate-y-2 scale-75 top-3 -z-10 origin-[0] peer-focus:start-0 rtl:peer-focus:translate-x-1/4 rtl:peer-focus:left-auto px-3 peer-placeholder-shown:scale-100 peer-placeholder-shown:translate-y-0 peer-focus:scale-x-75 peer-focus:-translate-y-3">Genere*</label>
                        </div>

    <div class="relative z-0 w-full mb-6 group bg-white">
      <input type="email" name="floating_email" id="floating_email" class="bg-gray-50 block py-3 px-0 text-sm rounded-lg w-full p-4 bg-transparent border  dark:bg-gray-50 text-gray-700 dark:placeholder-gray-50 dark:text-white peer" placeholder=" " required />
      <label for="floating_email" class="peer-focus:font-medium absolute text-sm text-gray-500 dark:text-gray-400 duration-300 transform -translate-y-6 scale-75 top-3 -z-10 origin-[0] peer-focus:start-0 rtl:peer-focus:translate-x-1/4 rtl:peer-focus:left-auto  px-3  peer-placeholder-shown:scale-100 peer-placeholder-shown:translate-y-0 peer-focus:scale-x-75 peer-focus:-translate-y-3">Email address*</label>
  </div>

  <div class="relative z-0 w-full mb-6 bg-white">
      <input type="text" name="floating_number" id="floating_email" class=" block py-3 px-0 text-sm rounded-lg w-full p-4 bg-transparent border  dark:bg-gray-50 text-gray-700 dark:placeholder-gray-50 dark:text-white peer" placeholder=" " pattern="[0-9]{3}-[0-9]{2}-[0-9]{3}" required />
      <label for="floating_number" class="peer-focus:font-medium absolute text-sm text-gray-500 dark:text-gray-400 duration-300 transform -translate-y-6 scale-75 top-3 -z-10 origin-[0] peer-focus:start-0 rtl:peer-focus:translate-x-1/4 rtl:peer-focus:left-auto  px-3 peer-placeholder-shown:scale-100 peer-placeholder-shown:translate-y-0 peer-focus:scale-x-75 peer-focus:-translate-y-3">Cellulare</label>

</div>
<div></div>

  <div class="flex text-lg">
  <svg viewBox="-0.5 0 25 25" fill="none" width="20px" height="30px" xmlns="http://www.w3.org/2000/svg"><g id="SVGRepo_bgCarrier" stroke-width="0"></g><g id="SVGRepo_tracerCarrier" stroke-linecap="round" stroke-linejoin="round"></g><g id="SVGRepo_iconCarrier">
    <path d="M12 21.5C17.1086 21.5 21.25 17.3586 21.25 12.25C21.25 7.14137 17.1086 3 12 3C6.89137 3 2.75 7.14137 2.75 12.25C2.75 17.3586 6.89137 21.5 12 21.5Z" stroke="#e72b6f" stroke-width="1.5" stroke-linecap="round" stroke-linejoin="round"></path> 
    <path d="M12.9309 8.15005C12.9256 8.39231 12.825 8.62272 12.6509 8.79123C12.4767 8.95974 12.2431
     9.05271 12.0008 9.05002C11.8242 9.04413 11.6533 8.98641 11.5093 8.884C11.3652 8.7816 11.2546
      8.63903 11.1911 8.47415C11.1275 8.30927 11.1139 8.12932 11.152 7.95675C11.19 7.78419 11.278 
      7.6267 11.405 7.50381C11.532 7.38093 11.6923 7.29814 11.866 7.26578C12.0397 7.23341 12.2192
       7.25289 12.3819 7.32181C12.5446 7.39072 12.6834 7.506 12.781 7.65329C12.8787 7.80057 12.9308
        7.97335 12.9309 8.15005ZM11.2909 16.5301V11.1501C11.2882 11.0556 11.3046 10.9615 11.3392
         10.8736C11.3738 10.7857 11.4258 10.7057 11.4922 10.6385C11.5585 10.5712 11.6378 10.518 
         11.7252 10.4822C11.8126 10.4464 11.9064 10.4286 12.0008 10.43C12.094 10.4299 12.1863 10.4487
          12.272 10.4853C12.3577 10.5218 12.4352 10.5753 12.4997 10.6426C12.5642 10.7099 12.6143 
          10.7895 12.6472 10.8767C12.6801 10.9639 12.6949 11.0569 12.6908 11.1501V16.5301C12.6908 
          16.622 12.6727 16.713 12.6376 16.7979C12.6024 16.8828 12.5508 16.96 12.4858 17.025C12.4208 
          17.09 12.3437 17.1415 12.2588 17.1767C12.1738 17.2119 12.0828 17.23 11.9909 17.23C11.899
           17.23 11.8079 17.2119 11.723 17.1767C11.6381 17.1415 11.5609 17.09 11.4959 17.025C11.4309
            16.96 11.3793 16.8828 11.3442 16.7979C11.309 16.713 11.2909 16.622 11.2909 16.5301Z" fill="#e72b6f">
        </path> </g></svg>
      <p class="">Perché è importante?</p>
     
    
    </div>
    
    <div></div>

    <div>  <p >Riceverai le nostre promazioni più importanti via SMS</p></div>
    </div>

   
         </div>


         
        
         <div class=" ">
    <h1>La tua Famiglia</h1>
    <div class="w-full h-64 bg-gray-300 flex flex-col justify-center items-center rounded-3xl">
        <div class="flex flex-col space-x-28 w-3/4">
            <a href="#" type="button" class="bg-[#E72B6F] mx-auto py-4 px-52 text-xl text-white rounded-full">+ AGGIUNGI FIGLIO</a>
            <div class="flex flex-row mt-4">
                <svg viewBox="-0.5 0 25 25" fill="none" width="20px" height="30px" xmlns="http://www.w3.org/2000/svg">
                    <g id="SVGRepo_bgCarrier" stroke-width="0"></g>
                    <g id="SVGRepo_tracerCarrier" stroke-linecap="round" stroke-linejoin="round"></g>
                    <g id="SVGRepo_iconCarrier">
                        <path d="M12 21.5C17.1086 21.5 21.25 17.3586 21.25 12.25C21.25 7.14137 17.1086 3 12 3C6.89137 3 2.75 7.14137 2.75 12.25C2.75 17.3586 6.89137 21.5 12 21.5Z" stroke="#e72b6f" stroke-width="1.5" stroke-linecap="round" stroke-linejoin="round"></path> 
                        <path d="M12.9309 8.15005C12.9256 8.39231 12.825 8.62272 12.6509 8.79123C12.4767 8.95974 12.2431 9.05271 12.0008 9.05002C11.8242 9.04413 11.6533 8.98641 11.5093 8.884C11.3652 8.7816 11.2546 8.63903 11.1911 8.47415C11.1275 8.30927 11.1139 8.12932 11.152 7.95675C11.19 7.78419 11.278 7.6267 11.405 7.50381C11.532 7.38093 11.6923 7.29814 11.866 7.26578C12.0397 7.23341 12.2192 7.25289 12.3819 7.32181C12.5446 7.39072 12.6834 7.506 12.781 7.65329C12.8787 7.80057 12.9308 7.97335 12.9309 8.15005ZM11.2909 16.5301V11.1501C11.2882 11.0556 11.3046 10.9615 11.3392 10.8736C11.3738 10.7857 11.4258 10.7057 11.4922 10.6385C11.5585 10.5712 11.6378 10.518 11.7252 10.4822C11.8126 10.4464 11.9064 10.4286 12.0008 10.43C12.094 10.4299 12.1863 10.4487 12.272 10.4853C12.3577 10.5218 12.4352 10.5753 12.4997 10.6426C12.5642 10.7099 12.6143 10.7895 12.6472 10.8767C12.6801 10.9639 12.6949 11.0569 12.6908 11.1501V16.5301C12.6908 16.622 12.6727 16.713 12.6376 16.7979C12.6024 16.8828 12.5508 16.96 12.4858 17.025C12.4208 17.09 12.3437 17.1415 12.2588 17.1767C12.1738 17.2119 12.0828 17.23 11.9909 17.23C11.899 17.23 11.8079 17.2119 11.723 17.1767C11.6381 17.1415 11.5609 17.09 11.4959 17.025C11.4309 16.96 11.3793 16.8828 11.3442 16.7979C11.309 16.713 11.2909 16.622 11.2909 16.5301Z" fill="#e72b6f"></path>
                    </g>
                </svg>
                <p class="">Perché è importante?</p>
            </div>
            <p class="ml-10">Lasciandoci i dati dei tuoi figli potremo offrirti un servizio sempre migliore e personalizzato sulle tue esigenze di genitore in più invieremo una sorpresa in occasione del loro compleanno</p>
        </div>
    </div>
</div>

        <div>
            <h2>La tua famiglia si sta allargando?</h2>
           
          
       
    </div>
</div>
        </div>

            </div>

            

            <Footer></Footer>
</template>



<style>
/* input[type="Date"]::-webkit-calendar-picker-indicator {
    display: none;
} */
input[type="Date"]::before {
    content: "\1F4C5";
    position: absolute;
    right: 10px;
    top: 50%;
    transform: translateY(-50%);
    color: #e72b6f; 
}


</style>



