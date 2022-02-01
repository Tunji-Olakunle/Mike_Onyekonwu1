<template>
    <header>
        <div class=" bg-neutral-200">
            <div class=" container mx-auto py-2 md:py-3 flex items-center justify-between">
                <div class=" flex justify-between items-center space-x-4 px-4 sm:px-0 ">
                    <P class=" font-normal text-[11px] md:text-[15px]"><span class=" font-semibold">Call us:</span> +2348 1528 9016</P>
                    <button class=" hidden md:block py-2 px-3 text-white bg-blue-700 transition-colors duration-300 hover:bg-[#1e4ac8]">MAKE AN APPOINTMENT </button>
                </div>
                <div class=" ">
                    <button class=" md:hidden  scale-[.60] md:scale-100 py-2 px-3 text-white bg-blue-700 transition-colors duration-300 hover:bg-[#1e4ac8]">MAKE AN APPOINTMENT </button>
                    <label class=" relative hidden md:block ">
                        <span class="absolute top-[7px] text-neutral-500 left-0 flex items-center pl-2">
                            <svg class="w-5 h-5" fill="none" stroke="currentColor" viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M21 21l-6-6m2-5a7 7 0 11-14 0 7 7 0 0114 0z"></path></svg>
                        </span>
                        <input class="text-neutral-500 rounded-sm placeholder:italic placeholder:text-neutral-800 block bg-neutral-100 w-full h-[35px] pl-[34px] pr-3 focus:outline-none focus:border-blue-700 focus:ring-blue-700 focus:ring-1 sm:text-sm" type="text" placeholder="Search">
                    </label>
                </div>
            </div>
        </div>
        
        <div class=" flex justify-center md:justify-between  items-center md:py-2 lg:py-3 container mx-auto ">
            <div class="flex items-center py-4 ">
                <!-- <img class="w-16 h-16" src="../assets/Mike.svg"> -->
                <p class="ml-1 font-semibold text-blue-700 text-[22px]">Prof. Mike O. Onyekonwu</p>
            </div>
            <div class=" hidden md:block space-x-1 ">
                <a class=" hover:bg-blue-700 p-2 hover:text-white transition-colors duration-[400ms] " href="">Home</a>
                <a class=" hover:bg-blue-700 p-2 hover:text-white transition-colors duration-[400ms] " href="">Mission</a>
                <a class=" hover:bg-blue-700 p-2 hover:text-white transition-colors duration-[400ms] " href="">Team</a>
                <a class=" hover:bg-blue-700 p-2 hover:text-white transition-colors duration-[400ms] " href="">Research</a>
                <a class=" hover:bg-blue-700 p-2 hover:text-white transition-colors duration-[400ms] " href="">About Us</a>
            </div>
        </div>
        <div class="  md:hidden bg-blue-700 text-white">
            <div class="px-3 md:px-0 container mx-auto py-3  flex justify-between ">
                <span class=" cursor-pointer">
                    <svg class="w-5 h-5" fill="none" stroke="currentColor" viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M4 6h16M4 12h8m-8 6h16"></path></svg>
                </span>
                <span class=" cursor-pointer">
                    <svg class="w-5 h-5" fill="none" stroke="currentColor" viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M21 21l-6-6m2-5a7 7 0 11-14 0 7 7 0 0114 0z"></path></svg>
                </span>
            </div> 
        </div>
       
    </header>
</template>

<script setup>
import { onBeforeMount, ref } from 'vue'
// const show = ref(false)

// onBeforeMount(()=>{
//      function checkWidth (){
//      if (window.innerWidth >= 1024){
//          show.value = true
//      }
//  }
// })

</script>

<style>

</style>