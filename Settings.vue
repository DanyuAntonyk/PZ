<template>
  <div class="sm:container mx-auto">
    <div class="flex justify-between space-x-10">
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
            <div class="flex-grow">
        
        <p class="text-3xl py-4"> Settings </p>
       <div class="flex  justify-between   ">
        <div class="bg-gray-100 px-4 w-1/2 py-4 m-2">
          
            <div class="flex text-2xl py-2  justify-between">
                <div> Profile info </div>
                
            </div>
            <div class="text-sm ">Email adress</div>

            <div class="flex my-3.5 h-10 rounded-full px-0.5  h-8 bg-white border justify-between space-x-4">

            <div class=" my-auto px-4">
                jsmith@gmail.com
                
            </div>
            <div class=" flex my-auto  rounded-full px-2  h-8 bg-white border">
                update
            </div>
        </div>

        <div class="text-sm ">Password</div>

        <div class="flex my-3.5 h-10 rounded-full px-0.5  h-8 bg-white border justify-between space-x-4">

            <div class=" px-4 my-auto">
                ...........
                
            </div>
            <div class=" flex  my-auto rounded-full px-2  h-8 bg-yellow-500 border text-white">
                Change
            </div>
        </div>
          </div>

          <div class="bg-gray-100 px-4 w-1/2 m-2">
          
            <div class="flex text-2xl py-4 justify-between">
                <div> Email notificatoin </div>
                
            </div>
            <input type="checkbox" class="form-checkbox">
                <span class="ml-2">Recive montly notification
                    </span>
                
            
  
          </div>
        </div>
       
    </div>

    </div>
  </div>
</template>
