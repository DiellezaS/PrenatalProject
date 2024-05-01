<template>
    
 <Navbar />
    <div class="max-w-screen-2xl mx-auto flex flex-col mt-16">
        <div class="flex mx-auto gap-32">
            <div class="w-1/4">
                <LaTuaCard />
            </div>

            <div class="w-3/4  my-12  rounded-3xl  text-xl">
                <h1 class="text-[#e72b6f] text-4xl gap-3 font-semibold mb-4">I tuoi dati</h1>
                
                
                <div class="bg-[#f7f7f7] w-full rounded-3xl">

                 
                        
    <div class="grid gap-6 mb-6 md:grid-cols-2 p-8 form-floating">
        
      
        <div class="grid grid-cols-2 relative z-0 text-gray-700 w-full mb-5 group bg-white">
      <input type="text" name="floating_name" id="floating_name" class="bg-gray-50 block p-4 text-sm rounded-lg  w-full  bg-transparent border  dark:bg-gray-50 text-gray-800 dark:placeholder-gray-50 dark:text-white peer" placeholder=" " required />
      <label for="floating_name" class="peer-focus:font-medium absolute text-sm text-gray-500 dark:text-gray-400 duration-300 transform -translate-y-6 scale-75 top-3 -z-10 origin-[0] peer-focus:start-0 rtl:peer-focus:translate-x-1/4 rtl:peer-focus:left-auto px-3 peer-placeholder-shown:scale-100 peer-placeholder-shown:translate-y-0 peer-focus:scale-x-75 peer-focus:-translate-y-2">Nome*</label>
  </div>
    

  <div class="relative z-0 w-full mb-5 group bg-white">
      <input type="text" name="floating_cognome" id="floating_cognome" class="bg-gray-50 block p-4 px-0 text-sm   rounded-lg  w-full  bg-transparent border  dark:bg-gray-50 text-gray-700 dark:placeholder-gray-50 dark:text-white peer" placeholder=" " required />
      <label for="floating_cognome" class="peer-focus:font-medium absolute text-sm text-gray-500 dark:text-gray-400 duration-300 transform -translate-y-6 scale-75 top-3 -z-10 origin-[0] peer-focus:start-0 rtl:peer-focus:translate-x-1/4 rtl:peer-focus:left-auto  px-3 peer-placeholder-shown:scale-100 peer-placeholder-shown:translate-y-0 peer-focus:scale-x-75 peer-focus:-translate-y-3">Cognome*</label>
  </div>

  <div class="relative z-0 w-full mb-5 group bg-white">
      <input type="Date" name="floating_data" id="floating_data" class="bg-gray-50 block py-3 px-0 text-sm   rounded-lg  w-full p-4 bg-transparent border  dark:bg-gray-50 text-gray-700 dark:placeholder-gray-50 dark:text-white peer" placeholder=" " required />
      <label for="floating_data" class="peer-focus:font-medium absolute text-sm text-gray-500 dark:text-gray-400 duration-300 transform -translate-y-2 scale-75 top-3 -z-10 origin-[0] peer-focus:start-0 rtl:peer-focus:translate-x-1/4 rtl:peer-focus:left-auto  px-3 peer-placeholder-shown:scale-100 peer-placeholder-shown:translate-y-0 peer-focus:scale-x-75 peer-focus:-translate-y-1">Data di nascita*</label>
  </div>

  <div class="relative z-0 w-full mb-5 group bg-white">
      <select name="floating_genere" id="floating_genere" class="bg-gray-50 block py-3 px-0 text-sm rounded-lg w-full p-4 bg-transparent border dark:bg-gray-50 text-gray-700 dark:placeholder-gray-50 dark:text-white peer" placeholder=" " required >
      <label for="floating_data" class="peer-focus:font-medium absolute text-sm text-gray-500 dark:text-gray-400 duration-300 transform -translate-y-2 scale-75 top-3 -z-10 origin-[0] peer-focus:start-0 rtl:peer-focus:translate-x-1/4 rtl:peer-focus:left-auto  px-3 peer-placeholder-shown:scale-100 peer-placeholder-shown:translate-y-0 peer-focus:scale-x-75 peer-focus:-translate-y-3">Genere*</label>
                <option>Femmina</option>
                <option>Uomo</option>
            </select>
    </div>

    <div class="relative z-0 w-full mb-5 group bg-white">
      <input type="email" name="floating_email" id="floating_email" class="bg-gray-50 block py-3 px-0 text-sm rounded-lg w-full p-4 bg-transparent border  dark:bg-gray-50 text-gray-700 dark:placeholder-gray-50 dark:text-white peer" placeholder=" " required />
      <label for="floating_email" class="peer-focus:font-medium absolute text-sm text-gray-500 dark:text-gray-400 duration-300 transform -translate-y-6 scale-75 top-3 -z-10 origin-[0] peer-focus:start-0 rtl:peer-focus:translate-x-1/4 rtl:peer-focus:left-auto  px-3  peer-placeholder-shown:scale-100 peer-placeholder-shown:translate-y-0 peer-focus:scale-x-75 peer-focus:-translate-y-3">Email address*</label>
  </div>

  <div class="relative z-0 w-full mb-5 group bg-white">
      <input type="text" name="floating_number" id="floating_email" class="bg-gray-50 block py-3 px-0 text-sm rounded-lg w-full p-4 bg-transparent border  dark:bg-gray-50 text-gray-700 dark:placeholder-gray-50 dark:text-white peer" placeholder=" " pattern="[0-9]{3}-[0-9]{2}-[0-9]{3}" required />
      <label for="floating_number" class="peer-focus:font-medium absolute text-sm text-gray-500 dark:text-gray-400 duration-300 transform -translate-y-6 scale-75 top-3 -z-10 origin-[0] peer-focus:start-0 rtl:peer-focus:translate-x-1/4 rtl:peer-focus:left-auto  px-3 peer-placeholder-shown:scale-100 peer-placeholder-shown:translate-y-0 peer-focus:scale-x-75 peer-focus:-translate-y-3">Cellulare</label>
  </div>
    
      
    </div>
   




                </div>


                    </div>
            </div>
            </div>
</template>

