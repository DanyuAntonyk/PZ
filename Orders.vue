<template>
  <div class="sm:container mx-auto">
    <div class="flex justify-between space-x-10">
     <div class="flex">
      <div class="flex item-start py-4 ">

      <div class="w-40 h-7 mr-2 flex-shrink-0">
    <ul>

      <li>
        <a href="#" class="flex px-4 py-1 hover:bg-gray-100">Account Dashboard</a>
      </li>

      <li>
        <a href="#" class="flex px-4 py-1 hover:bg-gray-100">Orders</a>
      </li>

      <li>
        <a href="#" class="flex px-4 py-1 hover:bg-gray-100">Returns</a>
      </li>

      <li>
        <a href="#" class="flex px-4 py-1 hover:bg-gray-100">Revards</a>
      </li>

      <li>
        <a href="#" class="flex px-4 py-1 hover:bg-gray-100">Addresses</a>
      </li>

      <li>
        <a href="#" class="flex px-4 py-1 hover:bg-gray-100">Settings</a>
      </li>
      
    </ul>
      </div>
        

      </div>

      </div>
      <div class="flex-grow">
        <div class="flex justify-between">
        <div class="text-3xl py-4"> Order #123763 </div>
        <div class="flex space-x-2 my-auto">
            <div class="rounded-full bg-yellow-100 text-yellow-600 h-8 px-4">Pending</div>
            <div class="rounded-full bg-white border h-8 px-4">Print</div>
            <div class="rounded-full bg-yellow-500 text-white h-8 px-4">Track</div>
        </div>
        </div>

        <div class="grid grid-cols-3 gap-4">

            <div class="col-start-1 col-end-2 bg-gray-100 px-4">

               <div class="border-b-2 border-gray-400 py-4 font-bold">Shipping Adress</div>
                <div class="py-4">
                        <p class="font-light">James Klen</p>
                        <p class="font-light">1232 E main street St</p>
                        <p class="font-light">San Diego, CA 23234</p>
                </div>
            </div>


            <div class="col-start-2 col-end-3 bg-gray-100 px-4">
                <div class="border-b-2 border-gray-400 py-4 font-bold">Payment Method</div>
                <div class="py-4 flex justify-between">
                       <div class="font-light">Mastercard</div>
                        <div class="font-light">****4321</div>
                </div>
            </div>


            <div class="col-start-3 col-end-4 bg-gray-100 px-4">
                <div class="border-b-2 border-gray-400 py-4 font-bold">Details</div>
                <div class="py-4">
                        <div class="flex justify-between py-1">
                            <div class="font-bold">Order Date</div>
                            <div class="font-light">12/25/2020</div>
                        </div>
                        <div class="flex justify-between py-1">
                           
                                <div class="font-bold">Carrier</div>
                                <div class="font-light">FED ex ground</div>
                            
                        </div>
                        <div class="flex  justify-between py-1">
                            <div class="font-bold">Tacking#</div>
                            <div class="font-light">123123</div>
                        </div>
                </div>
            </div>


            <div class="col-start-1 col-end-4 ">
                <div class="">
                        <div class="flex bg-gray-100 space-x-4 border-l border-r border-t p-4 bg-gray-100">
                            <div class="text-xl font-bold">Order contents</div>
                            <div class="text-lg font-light">Estimated Delivery: 21/12/2020</div>
                        </div>

                        <div class="border-l border-r border-b">
                            <div class="flex">
                                <div class="p-8 bg-gray-200 m-2">1</div>
                                <div class="my-auto mx-2">
                                  <div class="font-light">10 Animal leaf rake net with standart</div>
                                  <div class="flex space-x-4">
                                    <div class="font-bold text-lg">20.00 $</div>
                                  <div class="font-light text-sm my-auto">Qt:1</div>
                                </div>
                              </div>
                              </div>
                              <div class="flex">
                                <div class="p-8 bg-gray-200 m-2">1</div>
                                <div class="my-auto mx-2">
                                    <div class="font-light">Briliant wonders</div>
                                  <div class="flex space-x-4">
                                    <div class="font-bold text-lg">20.00 $</div>
                                  <div class="font-light text-sm my-auto">Qt:1</div>
                                  </div>
                                </div>
                            </div>
                            <div class="flex">
                                <div class="p-8 bg-gray-200 m-2">1</div>
                                <div class="my-auto mx-2">
                                    <div class="font-light">Briliant wonders</div>
                                  <div class="flex space-x-4">
                                    <div class="font-bold text-lg">20.00 $</div>
                                  <div class="font-light text-sm my-auto">Qt:1</div>
                                  </div>
                                 </div>
                            </div>
                            <div class="flex">
                                <div class="p-8 bg-gray-200 m-2">1</div>
                                <div class="my-auto mx-2">
                                  <div class="font-light">Briliant wonders</div>
                                  <div class="flex space-x-4">
                                  <div class="font-bold text-lg">20.00 $</div>
                                  <div class="font-light text-sm my-auto">Qt:1</div>
                                  </div>
                                </div>
                            </div>
                        </div>
                        
                </div>
            </div>
            <div class=" col-start-3 col-end-4 ml-28">
                <div class="flex justify-between px-2 py-2">
                    <div class="font-light">Subtotal</div>
                    <div class="font-light">$50.00</div>
                </div>
                <div class="flex justify-between px-2 py-2">
                    <div class="font-light">Shipping</div>
                    <div class="font-light">$2.00</div>
                </div>
                <div class="flex justify-between px-2 py-2">
                    <div class="font-light">Tax</div>
                    <div class="font-light">$5.00</div>
                </div>
                <div class="flex justify-between bg-gray-100 rounded-lg px-2 py-4">
                    <div class="font-light">Total</div>
                    <div class="font-light">$57.00</div>
                </div>
            </div>


        </div>
        
       
      

      
       
    </div>
    </div>
  </div>
</template>
