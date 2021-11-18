<template>
  <div class="bg-green-500 h-screen">
    
    <div class="bg-gray-800 grid grid-cols-2 h-auto border-8 border-black ">

      <div class="grid grid-cols-3 border-dashed">
        <h1 class="text-5xl text-white text-left ml-8 mt-8 font2">
         Calculator
        </h1>
        <h1 class="text-3xl text-gray-500 text-left font1 ml-59 mt-0">
         By Andres Zea
        </h1>

        
    
        
      </div>
       
      <div class="grid grid-cols-3">
        
          <button target="blank"  class="my-4 mx-10 facebook1 text-white font-semibold rounded-lg shadow-md hover:bg-green-700 focus:outline-none focus:ring-2 focus:ring-green-400 focus:ring-opacity-75">
            <a href="https://www.facebook.com/andresfelipe.zea">
             Facebook
            </a>
          </button>
         <button class="my-4 mx-10 github1 text-white font-semibold rounded-lg shadow-md hover:bg-green-700 focus:outline-none focus:ring-2 focus:ring-green-400 focus:ring-opacity-75">
          <a href="https://github.com/AndresZea2003">Github</a>  
          </button>
          <button class="my-4 mx-10 bg-red-600 text-white font-semibold rounded-lg shadow-md hover:bg-green-700 focus:outline-none focus:ring-2 focus:ring-green-400 focus:ring-opacity-75">
           <a href="https://www.youtube.com/channel/UCnVVCn92d-329QXd8WRp0VA">Youtube</a>  
          </button>

          

        
        
          
      
      </div>
      
    </div>
    <div class="bg-gray-600 grid grid-cols-2">
        <div class="bg-gray-400 mx-20 my-11 border-8 border-solid border-black">

          
          <div class="grid grid-cols-2 bg-gray-300">
            <input class="focus:ring-2 focus:ring-blue-600 object-right py-10 px-20 ml-20">
            <button class="border-2 focus:ring-blue-600 hover:border-gray-500 text-6xl rounded-full h-24 w-24 flex items-center justify-center bg-red-500 text-white ml-24">
             X
            </button>
          </div>
          <div class="flex grid grid-cols-4 gap-x-0 gap-y-5 justify-items-center">

            
             <button class="border-2 focus:ring-blue-600 hover:border-gray-500 text-6xl rounded-full h-24 w-24 flex items-center justify-center bg-gray-500 text-white">1</button>
             <button class="border-2 focus:ring-blue-600 hover:border-gray-500 text-6xl rounded-full h-24 w-24 flex items-center justify-center bg-gray-500 text-white">2</button>
             <button class="border-2 focus:ring-blue-600 hover:border-gray-500 text-6xl rounded-full h-24 w-24 flex items-center justify-center bg-gray-500 text-white">3</button>
             <button class="border-2 focus:ring-blue-600 hover:border-gray-500 text-6xl rounded-full h-24 w-24 flex items-center justify-center bg-green-700 text-white">÷</button>
             <button class="border-2 focus:ring-blue-600 hover:border-gray-500 text-6xl rounded-full h-24 w-24 flex items-center justify-center bg-gray-500 text-white">4</button>
            
             <button class="border-2 focus:ring-blue-600 hover:border-gray-500 text-6xl rounded-full h-24 w-24 flex items-center justify-center bg-gray-500 text-white">5</button>
             <button class="border-2 focus:ring-blue-600 hover:border-gray-500 text-6xl rounded-full h-24 w-24 flex items-center justify-center bg-gray-500 text-white">6</button>
             <button class="border-2 focus:ring-blue-600 hover:border-gray-500 text-6xl rounded-full h-24 w-24 flex items-center justify-center bg-green-700 text-white">×</button>
           

            
            <button class="border-2 focus:ring-blue-600 hover:border-gray-500 text-6xl rounded-full h-24 w-24 flex items-center justify-center bg-gray-500 text-white">7</button>
            <button class="border-2 focus:ring-blue-600 hover:border-gray-500 text-6xl rounded-full h-24 w-24 flex items-center justify-center bg-gray-500 text-white">8</button>
            <button class="border-2 focus:ring-blue-600 hover:border-gray-500 text-6xl rounded-full h-24 w-24 flex items-center justify-center bg-gray-500 text-white">9</button>
            <button class="border-2 focus:ring-blue-600 hover:border-gray-500 text-6xl rounded-full h-24 w-24 flex items-center justify-center bg-green-700 text-white">-</button>

            <button class="border-2 focus:ring-blue-600 hover:border-gray-500 text-6xl rounded-full h-24 w-24 flex items-center justify-center bg-green-700 text-white">C</button>
            <button class="border-2 focus:ring-blue-600 hover:border-gray-500 text-6xl rounded-full h-24 w-24 flex items-center justify-center bg-gray-500 text-white">0</button>
            <button class="border-2 focus:ring-blue-600 hover:border-gray-500 text-6xl rounded-full h-24 w-24 flex items-center justify-center bg-green-700 text-white">.</button>
            <button class="border-2 focus:ring-blue-600 hover:border-gray-500 text-6xl rounded-full h-24 w-24 flex items-center justify-center bg-green-700 text-white">=</button>
            

          </div>
        </div>
        <div class="bg-red-600">
          <h1 class="text-6xl text-red-400 text-right py-8 px-8">Historial</h1>
        </div>
     </div>
    
      
    
  <svg class="animate-bounce w-6 h-6 ...">
  <svg xmlns="http://www.w3.org/2000/svg"   viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round" class="feather feather-plus-circle"><circle cx="12" cy="12" r="10"></circle><line x1="12" y1="8" x2="12" y2="16"></line><line x1="8" y1="12" x2="16" y2="12"></line></svg>
</svg>

 
  <button class="my-4 mx-10 bg-red-600 text-white font-semibold rounded-lg shadow-md hover:bg-green-700 focus:outline-none focus:ring-2 focus:ring-green-400 focus:ring-opacity-75">
           Youtube
          </button>
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  </div>

  
 <icon width="100px"/>
 <icon width="100px"/>
 <MasIcon>safafaf</MasIcon>/> agsagaegegaegae
  <mas-icon/>
  





<div class="bg-gray-600 grid grid-cols-2">
  <div class="bg-blue-600">1</div>
  <div class="bg-red-600">2</div>
 </div>












</template>

<script>
import Facebool from './components/assets/Facebool.vue';
import Icon from './components/assets/Icon.vue';
import MasIcon from './components/assets/MasIcon.vue';
export default {
  components: {Icon, MasIcon, Facebool}
}
</script>
