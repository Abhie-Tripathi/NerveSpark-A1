<script>
import bmw from "../assets/bmw.PNG"
import header from "../assets/header.PNG"
import fiat from "../assets/fiat.PNG"
import volks from "../assets/volks.PNG"
import ford from "../assets/ford.PNG"
import merce from "../assets/merce.PNG"
</script>





<button data-drawer-target="logo-sidebar" data-drawer-toggle="logo-sidebar" aria-controls="logo-sidebar" type="button" class="inline-flex items-center p-2 mt-2 ml-3 text-sm text-gray-500 rounded-lg sm:hidden hover:bg-gray-100 focus:outline-none focus:ring-2 focus:ring-gray-200 dark:text-gray-400 dark:hover:bg-gray-700 dark:focus:ring-gray-600">
  <span class="sr-only">Open sidebar</span>
  <svg class="w-6 h-6" aria-hidden="true" fill="currentColor" viewBox="0 0 20 20" xmlns="http://www.w3.org/2000/svg">
     <path clip-rule="evenodd" fill-rule="evenodd" d="M2 4.75A.75.75 0 012.75 4h14.5a.75.75 0 010 1.5H2.75A.75.75 0 012 4.75zm0 10.5a.75.75 0 01.75-.75h7.5a.75.75 0 010 1.5h-7.5a.75.75 0 01-.75-.75zM2 10a.75.75 0 01.75-.75h14.5a.75.75 0 010 1.5H2.75A.75.75 0 012 10z"></path>
  </svg>
</button>

<aside id="logo-sidebar" class="fixed top-0 left-0 z-40 w-64 h-screen transition-transform -translate-x-full sm:translate-x-0" aria-label="Sidebar">
  <div class="h-full px-3 py-4 overflow-y-auto bg-gray-50  dark:bg-gray-800">
     <a href="/" class="flex items-center pl-2.5 mb-5">
        <img src={header} class="h-6 mr-3 sm:h-12" alt="Flowbite Logo" />
        <span class="ml-2 self-center text-xl font-semibold whitespace-nowrap dark:text-white">Cars24</span>
     </a>
     <ul class="space-y-2 font-medium">
        <li>
           <a href="/ford" class="flex items-center p-2 text-gray-900 rounded-lg dark:text-white hover:bg-gray-100 dark:hover:bg-gray-700 group">
            <img src={ford} class="h-6 mr-3 sm:h-8 bg-white rounded-full">
              <span class="flex-1 ml-2 whitespace-nowrap">Ford</span>
           </a>
        </li>
        <li>
           <a href="/volkswagon" class="flex items-center p-2 text-gray-900 rounded-lg dark:text-white hover:bg-gray-100 dark:hover:bg-gray-700 group">
            <img src={volks} class="h-6 mr-3 sm:h-8  bg-white rounded-full">
              <span class="flex-1 ml-2 whitespace-nowrap">Volkswagon</span>
           </a>
        </li>
        <li>
           <a href="/bmw" class="flex items-center p-2 text-gray-900 rounded-lg dark:text-white hover:bg-gray-100 dark:hover:bg-gray-700 group" >
            <img src={bmw} class="h-6 mr-3 sm:h-9  bg-white rounded-full">
              <span class="flex-1 ml-2 whitespace-nowrap">BMW</span>
           </a>
        </li>
        <li>
           <a href="/mercedise" class="flex items-center p-2 text-gray-900 rounded-lg dark:text-white hover:bg-gray-100 dark:hover:bg-gray-700 group">
            <img src={merce} class="h-6 mr-3 sm:h-9  bg-white rounded-full">
              <span class="flex-1 ml-2 whitespace-nowrap">Mercedise</span>
           </a>
        </li>
        <li>
           <a href="/fiat" class="flex items-center p-2 text-gray-900 rounded-lg dark:text-white hover:bg-gray-100 dark:hover:bg-gray-700 group">
            <img src={fiat} class="h-6 mr-3 sm:h-9  bg-white rounded-full">
              <span class="flex-1 ml-2 whitespace-nowrap">Fiat</span>
           </a>
        </li>
        <li>
           <a href="/products" class="flex items-center p-2 text-gray-900 rounded-lg dark:text-white hover:bg-gray-100 dark:hover:bg-gray-700 group">
              <svg class="flex-shrink-0 w-5 h-5 text-gray-500 transition duration-75 dark:text-gray-400 group-hover:text-gray-900 dark:group-hover:text-white" aria-hidden="true" xmlns="http://www.w3.org/2000/svg" fill="currentColor" viewBox="0 0 18 20">
                 <path d="M17 5.923A1 1 0 0 0 16 5h-3V4a4 4 0 1 0-8 0v1H2a1 1 0 0 0-1 .923L.086 17.846A2 2 0 0 0 2.08 20h13.84a2 2 0 0 0 1.994-2.153L17 5.923ZM7 9a1 1 0 0 1-2 0V7h2v2Zm0-5a2 2 0 1 1 4 0v1H7V4Zm6 5a1 1 0 1 1-2 0V7h2v2Z"/>
              </svg>
              <span class="flex-1 ml-3 whitespace-nowrap">Add New Card</span>
           </a>
        </li>
        
     </ul>
  </div>
</aside>





