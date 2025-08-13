<template>
  <div class="bg-green-500 h-screen">
    
    <AppHeader/>
    
  
  
    <div class="bg-gray-600 grid grid-cols-2">
        <div class="bg-gray-400 mx-20 my-11 border-8 border-solid border-black">

          
          <div class="grid grid-cols-2 bg-gray-300">
            <h1 class="text-3xl bg-gray-400 font1 text-white my-4 ml-4 py-3 px-2">{{text}}</h1>
            <button @click='cambiaText0()' class="border-2 focus:ring-blue-600 hover:border-gray-500 text-6xl rounded-full h-24 w-24 flex items-center justify-center bg-red-500 text-white ml-24">
             X
            </button>
          
          </div>
          <div class="flex grid grid-cols-4 gap-x-0 gap-y-5 justify-items-center">

            

            
             <button @click='cambiaText()' class="border-2 focus:ring-blue-600 hover:border-gray-500 text-6xl rounded-full h-24 w-24 flex items-center justify-center bg-gray-500 text-white">1</button>
             <button @click='cambiaText1()' class="border-2 focus:ring-blue-600 hover:border-gray-500 text-6xl rounded-full h-24 w-24 flex items-center justify-center bg-gray-500 text-white">2</button>
             <button @click='cambiaText2()' class="border-2 focus:ring-blue-600 hover:border-gray-500 text-6xl rounded-full h-24 w-24 flex items-center justify-center bg-gray-500 text-white">3</button>
             <button @click='cambiaText3()' class="border-2 focus:ring-blue-600 hover:border-gray-500 text-6xl rounded-full h-24 w-24 flex items-center justify-center bg-green-700 text-white">÷</button>
             <button @click='cambiaText4()' class="border-2 focus:ring-blue-600 hover:border-gray-500 text-6xl rounded-full h-24 w-24 flex items-center justify-center bg-gray-500 text-white">4</button>
            
             <button @click='cambiaText5()' class="border-2 focus:ring-blue-600 hover:border-gray-500 text-6xl rounded-full h-24 w-24 flex items-center justify-center bg-gray-500 text-white">5</button>
             <button @click='cambiaText6()' class="border-2 focus:ring-blue-600 hover:border-gray-500 text-6xl rounded-full h-24 w-24 flex items-center justify-center bg-gray-500 text-white">6</button>
             <button @click='cambiaText7()' class="border-2 focus:ring-blue-600 hover:border-gray-500 text-6xl rounded-full h-24 w-24 flex items-center justify-center bg-green-700 text-white">×</button>
           

            
            <button @click='cambiaText8()' class="border-2 focus:ring-blue-600 hover:border-gray-500 text-6xl rounded-full h-24 w-24 flex items-center justify-center bg-gray-500 text-white">7</button>
            <button @click='cambiaText9()' class="border-2 focus:ring-blue-600 hover:border-gray-500 text-6xl rounded-full h-24 w-24 flex items-center justify-center bg-gray-500 text-white">8</button>
            <button @click='cambiaText10()' class="border-2 focus:ring-blue-600 hover:border-gray-500 text-6xl rounded-full h-24 w-24 flex items-center justify-center bg-gray-500 text-white">9</button>
            <button @click='cambiaText11()' class="border-2 focus:ring-blue-600 hover:border-gray-500 text-6xl rounded-full h-24 w-24 flex items-center justify-center bg-green-700 text-white">-</button>

            <button @click='cambiaText12()' class="border-2 focus:ring-blue-600 hover:border-gray-500 text-6xl rounded-full h-24 w-24 flex items-center justify-center bg-green-700 text-white">C</button>
            <button @click='cambiaText13()' class="border-2 focus:ring-blue-600 hover:border-gray-500 text-6xl rounded-full h-24 w-24 flex items-center justify-center bg-gray-500 text-white">0</button>
            <button @click='cambiaText14()' class="border-2 focus:ring-blue-600 hover:border-gray-500 text-6xl rounded-full h-24 w-24 flex items-center justify-center bg-green-700 text-white">.</button>
            <button @click='cambiaText15()' class="border-2 focus:ring-blue-600 hover:border-gray-500 text-6xl rounded-full h-24 w-24 flex items-center justify-center bg-green-700 text-white">=</button>
            

          </div>
        </div>

        <div class="bg-red-600">
          <h1 class="text-6xl text-red-400 text-right py-8 px-8">Historial</h1>
        </div>
    </div>
    

  
  </div>

  






</template>

<script>
import Facebool from './components/assets/Facebool.vue';
import Icon from './components/assets/Icon.vue';
import MasIcon from './components/assets/MasIcon.vue';
import AppHeader from './components/AppHeader.vue'
import { ref } from 'vue';
export default {
  components: {Icon, MasIcon, Facebool, AppHeader},

  setup() {
    const text = ref('Escribe una operacion :D')
    const cambiaText = () => {
      text.value = text.value+'1'
    }
    const cambiaText0 = () => {
      text.value = ''
    }
    const cambiaText1 = () => {
      text.value = text.value+'2'
    }
    const cambiaText2 = () => {
      text.value = text.value+'3'
    }
    const cambiaText3 = () => {
      text.value = text.value+'÷'
    }
    const cambiaText4 = () => {
      text.value = text.value+'4'
    }
    const cambiaText5 = () => {
      text.value = text.value+'5'
    }
    const cambiaText6 = () => {
      text.value = text.value+'6'
    }
    const cambiaText7 = () => {
      text.value = text.value+'×'
    }
    const cambiaText8 = () => {
      text.value = text.value+'7'
    }
    const cambiaText9 = () => {
      text.value = text.value+'8'
    }
    const cambiaText10 = () => {
      text.value = text.value+'9'
    }
    const cambiaText11 = () => {
      text.value = text.value+'-'
    }
    const cambiaText12 = () => {
      text.value = text.value+'+'
    }
    const cambiaText13 = () => {
      text.value = text.value+'0'
    }
    const cambiaText14 = () => {
      text.value = text.value+'.'
    }
    const cambiaText15 = () => {
      text.value = text.value+'='
    }
   
    return {text, cambiaText, cambiaText0, cambiaText1, cambiaText2, cambiaText3, cambiaText4, cambiaText5, cambiaText6, cambiaText7, cambiaText8, cambiaText9, cambiaText10, cambiaText11, cambiaText12, cambiaText13, cambiaText14, cambiaText15}
  }
}
</script>

