<template>
    
    <Navbar />
       <div class=" lg:w-[65%] mx-auto md:flex flex-col mt-16">
           <div class="md:flex mx-auto gap-4">
               <div >
                   <LaTuaCard />
               </div>
   
               <div class="w-full my-6 rounded-3xl text-xl p-4">
                   <h1 class="text-[#e72b6f] md:text-3xl text-2xl px-4 font-bold md:font-semibold my-6">I tuoi dati</h1>
                   
                   <div class="bg-[#f7f7f7] w-full rounded-3xl md:h-[340px] ">
                       <div class="grid gap-x-5 mb-5 md:grid-cols-2 md:p-12 p-6 pt-8 form-floating">
                           <div class="relative z-0 text-gray-700 w-full mb-4 group bg-white">
                               <input type="text" name="floating_name" id="floating_name" class="bg-gray-50 block p-3 text-sm rounded-lg w-full bg-transparent border-2 border-gray-300 dark:bg-gray-50 text-gray-800 dark:placeholder-gray-50 dark:text-white peer" placeholder=" " required />
                               <label for="floating_name" class="peer-focus:font-medium absolute text-sm text-gray-500 dark:text-gray-400 duration-300 transform -translate-y-4 scale-75 top-3 -z-10 origin-[0] peer-focus:start-0 rtl:peer-focus:translate-x-1/4 rtl:peer-focus:left-auto px-3 peer-placeholder-shown:scale-100 peer-placeholder-shown:translate-y-0 peer-focus:scale-x-75 peer-focus:-translate-y-2">Nome*</label>
                           </div>
   
                           <div class="relative z-0 text-gray-700 w-full mb-4 group bg-white">
                               <input type="text" name="floating_cognome" id="floating_cognome" class="bg-gray-50 block p-3 text-sm rounded-lg w-full bg-transparent border-2 border-gray-300 dark:bg-gray-50 text-gray-700 dark:placeholder-gray-50 dark:text-white peer" placeholder=" " required />
                               <label for="floating_cognome" class="peer-focus:font-medium absolute text-sm text-gray-500 dark:text-gray-400 duration-300 transform -translate-y-4 scale-75 top-3 -z-10 origin-[0] peer-focus:start-0 rtl:peer-focus:translate-x-1/4 rtl:peer-focus:left-auto px-3 peer-placeholder-shown:scale-100 peer-placeholder-shown:translate-y-0 peer-focus:scale-x-75 peer-focus:-translate-y-3">Cognome*</label>
                           </div>
   
   
   
   
                           <div class="relative z-0 w-full mb-4 group bg-white">
       <input type="Date" name="floating_data" id="floating_data" class="bg-gray-50 block py-3 px-3 text-sm rounded-lg w-full p-3 bg-transparent border-2 border-gray-300 dark:bg-gray-50 text-gray-700 dark:placeholder-gray-50 dark:text-white peer" placeholder=" " required />
       <label for="floating_data" class="peer-focus:font-medium absolute text-sm text-gray-500 dark:text-gray-400 duration-300 transform -translate-y-3 scale-100 top-3 -z-10 origin-[0] peer-focus:start-0 rtl:peer-focus:translate-x-1/4 rtl:peer-focus:left-auto px-3 peer-placeholder-shown:scale-100 peer-placeholder-shown:translate-y-0 peer-focus:scale-x-75 peer-focus:-translate-y-3">Data di nascita*</label>
   </div>
   
     <div class="relative z-0 w-full mb-4 group bg-white">
                               <select name="floating_genere" id="floating_genere" class="bg-gray-50 block py-3 px-4 p-3 text-sm rounded-lg w-full bg-transparent border-2 border-gray-300 dark:bg-gray-50 text-gray-700 dark:placeholder-gray-50 dark:text-white peer" placeholder=" " required >
                                   <option>Femmina</option>
                                   <option>Uomo</option>
                               </select>
                               <label for="floating_genere" class="peer-focus:font-medium absolute text-sm text-gray-500 dark:text-gray-400 duration-300 transform -translate-y-2 scale-100 top-3 -z-10 origin-[0] peer-focus:start-0 rtl:peer-focus:translate-x-1/4 rtl:peer-focus:left-auto px-3 peer-placeholder-shown:scale-100 peer-placeholder-shown:translate-y-0 peer-focus:scale-x-75 peer-focus:-translate-y-3">Genere*</label>
                           </div>
   
       <div class="relative z-0 w-full mb-4 group bg-white">
         <input type="email" name="floating_email" id="floating_email" class="bg-gray-50 block py-3 px-0 text-sm rounded-lg w-full p-3 bg-transparent border-2 border-gray-300 dark:bg-gray-50 text-gray-700 dark:placeholder-gray-50 dark:text-white peer" placeholder=" " required />
         <label for="floating_email" class="peer-focus:font-medium absolute text-sm text-gray-500 dark:text-gray-400 duration-300 transform -translate-y-6 scale-75 top-3 -z-10 origin-[0] peer-focus:start-0 rtl:peer-focus:translate-x-1/4 rtl:peer-focus:left-auto  px-3  peer-placeholder-shown:scale-100 peer-placeholder-shown:translate-y-0 peer-focus:scale-x-75 peer-focus:-translate-y-3">Email address*</label>
     </div>
   
     <div class="relative z-0 w-full mb-4 bg-white">
         <input type="text" name="floating_number" id="floating_email" class=" block py-3 px-0 text-sm rounded-lg w-full p-3 bg-transparent border-2 border-gray-300 dark:bg-gray-50 text-gray-700 dark:placeholder-gray-50 dark:text-white peer" placeholder=" " pattern="[0-9]{3}-[0-9]{2}-[0-9]{3}" required />
         <label for="floating_number" class="peer-focus:font-medium absolute text-sm text-gray-500 dark:text-gray-400 duration-300 transform -translate-y-6 scale-75 top-3 -z-10 origin-[0] peer-focus:start-0 rtl:peer-focus:translate-x-1/4 rtl:peer-focus:left-auto  px-3 peer-placeholder-shown:scale-100 peer-placeholder-shown:translate-y-0 peer-focus:scale-x-75 peer-focus:-translate-y-3">Cellulare</label>
   
   </div>
   <div></div>
   
   
     <div class="flex md:text-lg  text-base">
        <span>
     <svg viewBox="-0.5 0 25 25" fill="none" width="40px" height="30px" xmlns="http://www.w3.org/2000/svg"><g id="SVGRepo_bgCarrier" stroke-width="0"></g><g id="SVGRepo_tracerCarrier" stroke-linecap="round" stroke-linejoin="round"></g><g id="SVGRepo_iconCarrier">
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
           </path> </g></svg></span>
         <p class="text-[#e72b6f] font-medium leading-0">Perché è importante?</p>
       </div>
       
       <div></div>
   
       <div class="-translate-y-2 text-base tracking-tighter w-4/5 md:w-full leading-5 text-gray-500 mx-10">  <p >Riceverai le nostre promazioni più importanti via SMS</p></div>
       </div>
   
      
            </div>
   
            <div class=" ">
                <h1 class="text-[#E72B6F] md:text-3xl text-2xl  font-semibold my-8 md:my-12">La tua famiglia</h1>
       <div class="w-full md:h-64 bg-[#f7f7f7] flex flex-col justify-center items-center rounded-3xl p-3">
           <div class="flex flex-col md:w-[80%] w-full md:space-x-12  ">
               <a href="#" type="button" class="bg-[#E72B6F] mx-auto md:py-3 py-3  w-full md:w-4/5 md:mt-12 mt-6 text-center text-xl text-white rounded-full">+ AGGIUNGI FIGLIO</a>
              <div class="flex flex-row translate-y-8 md:translate-x-6 ">
                 <span >  <svg viewBox="-0.5 0 25 25" fill="none" width="40px" height="30px" xmlns="http://www.w3.org/2000/svg">
                       <g id="SVGRepo_bgCarrier" stroke-width="2"></g>
                       <g id="SVGRepo_tracerCarrier" stroke-linecap="round" stroke-linejoin="round"></g>
                       <g id="SVGRepo_iconCarrier">
                           <path d="M12 21.5C17.1086 21.5 21.25 17.3586 21.25 12.25C21.25 7.14137 17.1086 3 12 3C6.89137 3 2.75 7.14137 2.75 12.25C2.75 17.3586 6.89137 21.5 12 21.5Z" stroke="#e72b6f" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"></path> 
                           <path d="M12.9309 8.15005C12.9256 8.39231 12.825 8.62272 12.6509 8.79123C12.4767 8.95974 12.2431 9.05271 12.0008 9.05002C11.8242 9.04413 11.6533 8.98641 11.5093 8.884C11.3652 8.7816 11.2546 8.63903 11.1911 8.47415C11.1275 8.30927 11.1139 8.12932 11.152 7.95675C11.19 7.78419 11.278 7.6267 11.405 7.50381C11.532 7.38093 11.6923 7.29814 11.866 7.26578C12.0397 7.23341 12.2192 7.25289 12.3819 7.32181C12.5446 7.39072 12.6834 7.506 12.781 7.65329C12.8787 7.80057 12.9308 7.97335 12.9309 8.15005ZM11.2909 16.5301V11.1501C11.2882 11.0556 11.3046 10.9615 11.3392 10.8736C11.3738 10.7857 11.4258 10.7057 11.4922 10.6385C11.5585 10.5712 11.6378 10.518 11.7252 10.4822C11.8126 10.4464 11.9064 10.4286 12.0008 10.43C12.094 10.4299 12.1863 10.4487 12.272 10.4853C12.3577 10.5218 12.4352 10.5753 12.4997 10.6426C12.5642 10.7099 12.6143 10.7895 12.6472 10.8767C12.6801 10.9639 12.6949 11.0569 12.6908 11.1501V16.5301C12.6908 16.622 12.6727 16.713 12.6376 16.7979C12.6024 16.8828 12.5508 16.96 12.4858 17.025C12.4208 17.09 12.3437 17.1415 12.2588 17.1767C12.1738 17.2119 12.0828 17.23 11.9909 17.23C11.899 17.23 11.8079 17.2119 11.723 17.1767C11.6381 17.1415 11.5609 17.09 11.4959 17.025C11.4309 16.96 11.3793 16.8828 11.3442 16.7979C11.309 16.713 11.2909 16.622 11.2909 16.5301Z" fill="#e72b6f"></path>
                       </g>
                   </svg></span></div>
        
            <div>
               <p class="text-[#e72b6f] md:ml-16 ml-10  font-medium ">Perché è importante?</p>
               <p class="md:ml-16 ml-10 md:text-[16px] md:leading-5  font-light text-base tracking-normal md:tracking-tight w-3/4 mb-6">Lasciandoci i dati dei tuoi figli potremo offrirti un servizio sempre migliore e personalizzato sulle tue esigenze di genitore in più invieremo una sorpresa in occasione del loro compleanno.</p>
           </div>
        </div>
       </div>
   </div>
   
           <div>
            <h2 class="text-[#E72B6F]  text-xl font-semibold px-2 my-4">La tua famiglia si sta allargando?</h2>

<div class="relative max-w-sm md:mx-4 mx-auto">
   
    <input type="date" class="bg-gray-50 border border-gray-300 text-gray-900 text-sm rounded-lg focus:ring-blue-500 focus:border-blue-500 block w-full ps-10 p-2.5 dark:bg-gray-700 dark:border-gray-600 dark:placeholder-gray-400 dark:text-white dark:focus:ring-blue-500 dark:focus:border-blue-500" placeholder="Select date">
</div>

   

       </div>



       <div>
        <h1 class="text-[#E72B6F] md:text-3xl text-2xl font-semibold px-2 mt-10">Dati aggiuntivi</h1>
        <div class="bg-[#f7f7f7] w-full rounded-3xl">
                      
                        <div class="mt-8 grid gap-x-6 gap-y-2 sm:grid-cols-4 p-6 md:p-12">
        <div class="sm:col-span-3 relative z-0 w-full mb-2 group bg-white">
            <input type="text" name="indirizzo" id="indirizzo"  class="bg-gray-50 block p-3 text-base rounded-lg w-full bg-transparent border border-gray-300 dark:bg-gray-50 text-gray-700 dark:placeholder-gray-50 dark:text-white peer" placeholder=" " required />
            <label for="floating_cognome" class="peer-focus:font-medium absolute text-base text-gray-500 dark:text-gray-400 duration-300 transform scale-75 top-3 -z-10 origin-[0] peer-focus:start-0 rtl:peer-focus:translate-x-1/4 rtl:peer-focus:left-auto px-3 peer-placeholder-shown:scale-100 peer-placeholder-shown:translate-y-0 peer-focus:scale-x-75 peer-focus:-translate-y-3">Indirizzo</label>
     
        </div>

        <div class="sm:col-span-1 relative z-0 w-full mb-3 group bg-white">

          <input type="text" name="nr-civico" id="nr-civico"  class="bg-gray-50 block p-3 text-sm rounded-lg w-full bg-transparent border border-gray-300 dark:bg-gray-50 text-gray-700 dark:placeholder-gray-50 dark:text-white peer" placeholder=" " required />
            <label for="nr-civico" class="peer-focus:font-medium absolute text-base text-gray-500 dark:text-gray-400 duration-300 transform scale-75 top-3 -z-10 origin-[0] peer-focus:start-0 rtl:peer-focus:translate-x-1/4 rtl:peer-focus:left-auto px-3 peer-placeholder-shown:scale-100 peer-placeholder-shown:translate-y-0 peer-focus:scale-x-75 peer-focus:-translate-y-3">Nr.civico</label>
     
        </div>


        <div class="sm:col-span-1 relative z-0 w-full mb-2 group bg-white">
     
          <input type="text" name="cap" id="cap"  class="bg-gray-50 block p-3 text-sm rounded-lg w-full border border-gray-300 bg-transparent  dark:bg-gray-50 text-gray-700 dark:placeholder-gray-50 dark:text-white peer" placeholder=" " required />
            <label for="cap" class="peer-focus:font-medium absolute text-base text-gray-500 dark:text-gray-400 duration-300 transform  scale-75 top-3 -z-10 origin-[0] peer-focus:start-0 rtl:peer-focus:translate-x-1/4 rtl:peer-focus:left-auto px-3 peer-placeholder-shown:scale-100 peer-placeholder-shown:translate-y-0 peer-focus:scale-x-75 peer-focus:-translate-y-3">Cap</label>
     
        </div>

        <div class="sm:col-span-3 relative z-0 w-full mb-2 group bg-white">
    

          <input type="text" name="Città" id="Città"  class="bg-gray-50 block p-3 text-sm rounded-lg w-full bg-transparent border border-gray-300 dark:bg-gray-50 text-gray-700 dark:placeholder-gray-50 dark:text-white peer" placeholder=" " required />
            <label for="Città" class="peer-focus:font-medium absolute text-base text-gray-500 dark:text-gray-400 duration-300 transform  scale-75 top-3 -z-10 origin-[0] peer-focus:start-0 rtl:peer-focus:translate-x-1/4 rtl:peer-focus:left-auto px-3 peer-placeholder-shown:scale-100 peer-placeholder-shown:translate-y-0 peer-focus:scale-x-75 peer-focus:-translate-y-3">Città</label>
     
        </div>

        <div class="sm:col-span-4 relative z-0 w-full mb-6 group bg-white ">
        
          
          <input type="text" name="Provincia" id="Provincia"  class="bg-gray-50 block p-3 text-sm rounded-lg w-full bg-transparent border border-gray-300 dark:bg-gray-50 text-gray-700 dark:placeholder-gray-50 dark:text-white peer" placeholder=" " required />
            <label for="Provincia" class="peer-focus:font-medium absolute text-base text-gray-500 dark:text-gray-400 duration-300 transform  scale-75 top-3 -z-10 origin-[0] peer-focus:start-0 rtl:peer-focus:translate-x-1/4 rtl:peer-focus:left-auto px-3 peer-placeholder-shown:scale-100 peer-placeholder-shown:translate-y-0 peer-focus:scale-x-75 peer-focus:-translate-y-3">Provincia</label>
     
        </div>


 
   </div>

</div>

<div class="flex flex-col gap-6 mt-10">
    <h1 class="text-[#E72B6F] md:text-3xl text-2xl font-bold md:font-semibold px-2 md:my-4">I tuoi consensi</h1>


    <div class="bg-[#f7f7f7] w-full rounded-3xl p-4 md:p-10">
  
    <div class="hidden md:flex flex-row items-center"> 
        <label class="cursor-pointer">
            <input type="checkbox" value="" class="sr-only peer" checked>
            <div class="relative w-11 h-6 bg-gray-200 rounded-full peer dark:bg-gray-700 peer-focus:ring-2 peer-focus:ring-[#fa3541] dark:peer-focus:ring-[#fa3541] peer-checked:after:translate-x-full rtl:peer-checked:after:-translate-x-full rotate-180 peer-checked:after:border-white after:content-[''] after:absolute after:top-0.5 after:start-[2px] after:bg-white after:border-gray-300 after:border after:rounded-full after:h-5 after:w-5 after:transition-all dark:border-gray-600 peer-checked:bg-[#fa3541]"></div>
        </label>
        <h2 class="text-[#E72B6F] text-xl font-medium ml-4">VUOI RICEVERE LE NOSTRE COMUNICAZIONI?</h2>
    </div>

    <div class="md:hidden flex flex-col items-start">
        <h2 class="text-[#E72B6F] text-xl font-medium mt-4 mb-2">VUOI RICEVERE LE NOSTRE COMUNICAZIONI?</h2>
    </div>

    <div class="md:mx-20 md:my-4 font-normal text-base md:font-light md:text-lg tracking-tighter w-[90%] leading-5">
        <p>Acconsento a essere contattato/a dalla Società tramite posta ordinaria, email e/o notifiche push, SMS e/o MMS e/ o applicazioni mobili di messaggistica per la promozione di prodotti, servizi, distribuzione di materiale a carattere informativo, pubblicitario e promozionale, eventi, invio di newsletter e pubblicazioni (Articolo 1, lettera d) dell'Informativa privacy. (opzionale)</p>
        <p class="text-[#fa3541] mt-2 font-medium">Senza il tuo consenso non potremo inviarti le nostre offerte.</p>
    </div>


    <label class="cursor-pointer md:hidden flex py-6">
            <input type="checkbox" value="" class="sr-only peer" checked>
            <div class="relative w-11 h-6 bg-gray-200 rounded-full peer dark:bg-gray-700 peer-focus:ring-2 peer-focus:ring-[#fa3541] dark:peer-focus:ring-[#fa3541] peer-checked:after:translate-x-full rtl:peer-checked:after:-translate-x-full rotate-180 peer-checked:after:border-white after:content-[''] after:absolute after:top-0.5 after:start-[2px] after:bg-white after:border-gray-300 after:border after:rounded-full after:h-5 after:w-5 after:transition-all dark:border-gray-600 peer-checked:bg-[#fa3541]"></div>
        </label>
</div>


    <div class="bg-[#f7f7f7] w-full rounded-3xl p-4 md:p-8">
    <div class="hidden md:flex flex-row">
        <label class=" cursor-pointer ">
  <input type="checkbox" value="" class="sr-only peer" checked>
  <div class="relative w-11 h-6 bg-gray-200 rounded-full peer dark:bg-gray-700 peer-focus:ring-2 peer-focus:ring-[#fa3541] dark:peer-focus:ring-[#fa3541] peer-checked:after:translate-x-full rtl:peer-checked:after:-translate-x-full rotate-180 peer-checked:after:border-white after:content-[''] after:absolute after:top-0.5 after:start-[2px] after:bg-white after:border-gray-300 after:border after:rounded-full after:h-5 after:w-5 after:transition-all dark:border-gray-600 peer-checked:bg-[#fa3541]"></div>
</label>
        <h2 class="text-[#E72B6F] text-xl font-medium mx-10">VUOI RICEVERE OFFERTE PERSONALIZZATE?</h2>
    </div>
   
    <div class="md:hidden flex flex-col items-start">
        <h2 class="text-[#E72B6F] text-xl font-medium mt-4 mb-2">VUOI RICEVERE OFFERTE PERSONALIZZATE?</h2>
    </div>
        <div class="md:mx-20 md:my-4 font-normal text-base md:font-light md:text-lg  tracking-tight w-[90%]  leading-5">
        <p>Acconsento affinché la Società possa svolgere analisi - attraverso un processo automatizzato - volte a determinare il profilo dell'Interessato per adeguare le attività di marketing alle esigenze dell'Interessato (Articolo 1, lettera e) dell'Informativa privacy. (opzionale)</p>
        <p class="text-[#fa3541] mt-2 font-medium">Non potrai ricevere offerte esclusive e personalizzate.</p>
        </div>

        <label class="cursor-pointer md:hidden flex py-6">
            <input type="checkbox" value="" class="sr-only peer" checked>
            <div class="relative w-11 h-6 bg-gray-200 rounded-full peer dark:bg-gray-700 peer-focus:ring-2 peer-focus:ring-[#fa3541] dark:peer-focus:ring-[#fa3541] peer-checked:after:translate-x-full rtl:peer-checked:after:-translate-x-full rotate-180 peer-checked:after:border-white after:content-[''] after:absolute after:top-0.5 after:start-[2px] after:bg-white after:border-gray-300 after:border after:rounded-full after:h-5 after:w-5 after:transition-all dark:border-gray-600 peer-checked:bg-[#fa3541]"></div>
        </label>
   </div>



   <div class="bg-[#f7f7f7] w-full rounded-3xl p-4 md:p-8">
       <div class="hidden md:flex">
        <label class=" items-center  cursor-pointer ">
  <input type="checkbox" value="" class="sr-only peer" checked>
  <div class="relative w-11 h-6 bg-gray-200 rounded-full peer dark:bg-gray-700 peer-focus:ring-2  peer-focus:ring-[#fa3541] dark:peer-focus:ring-[#fa3541] peer-checked:after:translate-x-full rtl:peer-checked:after:-translate-x-full rotate-180 peer-checked:after:border-white after:content-[''] after:absolute after:top-0.5 after:start-[2px] after:bg-white after:border-gray-300 after:border after:rounded-full after:h-5 after:w-5 after:transition-all dark:border-gray-600 peer-checked:bg-[#fa3541]"></div>
</label>
            <h2 class="text-[#E72B6F] text-xl font-medium mx-10">POSSIAMO CHIEDERE LA TUA OPINIONE CON I NOSTRI SONDAGGI?</h2>
    </div>
   
    <div class="md:hidden flex flex-col items-start">
        <h2 class="text-[#E72B6F] text-xl font-medium mt-4 mb-2">POSSIAMO CHIEDERE LA TUA OPINIONE CON I NOSTRI SONDAGGI?</h2>
    </div>

        <div class="md:mx-20 md:my-4 font-normal text-base md:font-light md:text-lg  tracking-tight  w-[90%] leading-5">
        <p>Acconsento a essere contattato dalla Società o da società da questa incaricate (anche tramite chiamata di un operatore) per lo svolgimento di analisi e ricerche di mercato, anche in relazione al grado di soddisfazione dell'Interessato (Articolo 1, lettera f) dell'Informativa privacy. (opzionale)</p>
    
        </div>
        <label class="cursor-pointer md:hidden flex py-6">
            <input type="checkbox" value="" class="sr-only peer" checked>
            <div class="relative w-11 h-6 bg-gray-200 rounded-full peer dark:bg-gray-700 peer-focus:ring-2 peer-focus:ring-[#fa3541] dark:peer-focus:ring-[#fa3541] peer-checked:after:translate-x-full rtl:peer-checked:after:-translate-x-full rotate-180 peer-checked:after:border-white after:content-[''] after:absolute after:top-0.5 after:start-[2px] after:bg-white after:border-gray-300 after:border after:rounded-full after:h-5 after:w-5 after:transition-all dark:border-gray-600 peer-checked:bg-[#fa3541]"></div>
        </label>
    </div>


    <div class="bg-[#f7f7f7] w-full rounded-3xl p-4 md:p-8 ">
    <div class="hidden md:flex">
        <label class=" items-center  cursor-pointer ">
  <input type="checkbox" value="" class="sr-only peer" checked>
  <div class="relative w-11 h-6 bg-gray-200 rounded-full peer dark:bg-gray-700 peer-focus:ring-2 peer-focus:ring-[#fa3541] dark:peer-focus:ring-[#fa3541] peer-checked:after:translate-x-full rtl:peer-checked:after:-translate-x-full rotate-180 peer-checked:after:border-white after:content-[''] after:absolute after:top-0.5 after:start-[2px] after:bg-white after:border-gray-300 after:border after:rounded-full after:h-5 after:w-5 after:transition-all dark:border-gray-600 peer-checked:bg-[#fa3541]"></div>
</label>
            <h2 class="text-[#E72B6F] text-xl font-medium mx-10 tracking-tight">POSSIAMO CONDIVIDERE I TUOI DATI CON ALTRE SOCIETÀ DEL NOSTRO GRUPPO?</h2>
    </div>
   

    <div class="md:hidden flex flex-col items-start">
        <h2 class="text-[#E72B6F] text-xl font-medium mt-4 mb-2">POSSIAMO CONDIVIDERE I TUOI DATI CON ALTRE SOCIETÀ DEL NOSTRO GRUPPO?</h2>
    </div>
        <div class="md:mx-20 md:my-4 font-normal text-base md:font-light md:text-lg tracking-tighter  w-[90%] leading-5">
        <p>Acconsento alla comunicazione dei dati da parte della Società ad altre società appartenenti al medesimo gruppo a cui appartiene la Società e/o a soggetti terzi per il perseguimento delle finalità per le quali ho prestato il mio consenso al Titolare. (opzionale)</p>

        </div>
        <label class="cursor-pointer md:hidden flex py-6">
            <input type="checkbox" value="" class="sr-only peer" checked>
            <div class="relative w-11 h-6 bg-gray-200 rounded-full peer dark:bg-gray-700 peer-focus:ring-2 peer-focus:ring-[#fa3541] dark:peer-focus:ring-[#fa3541] peer-checked:after:translate-x-full rtl:peer-checked:after:-translate-x-full rotate-180 peer-checked:after:border-white after:content-[''] after:absolute after:top-0.5 after:start-[2px] after:bg-white after:border-gray-300 after:border after:rounded-full after:h-5 after:w-5 after:transition-all dark:border-gray-600 peer-checked:bg-[#fa3541]"></div>
        </label>
   </div>

   </div>

<div class="flex">
    <a href="#" type="button" class="text-center bg-[#E72B6F] mx-auto py-3 md:w-3/5 w-full my-16 text-xl text-white rounded-full">SALVA LE MODIFICHE</a>
</div>
      </div>
   </div>
           </div>
   
               </div>
               <Footer></Footer>
   </template>
   

   
   <style>
.height{
    height: 370px;
}
</style>



