<script setup>
import { ref } from 'vue'


const allImg = {
    src: '//img.icons8.com/?size=512&id=12244&format=png',
    src2:'//img.icons8.com/?size=512&id=75&format=png'
  }
  
const imgShow = ref(true);
</script>

<template>
  <section class="container mx-auto flex items-center flex-col">
        <h1 class="text-center text-2xl py-10">Assignment</h1>
        <p class="p-5">Make These Buttons Work</p>
        <div class="flex justify-between space-x-6">
            <div class="p-10 border w-96 flex flex-col space-y-5">
                <button @click="imgShow = !imgShow" class="bg-blue-500 hover:bg-blue-700 text-white font-bold py-2 px-4 rounded">
                    Light 1 {{ imgShow == false ? 'off'  : ' on'}}
                </button>
                <button class="bg-blue-500 hover:bg-blue-700 text-white font-bold py-2 px-4 rounded">
                    Light 2 On
                </button>
                <button class="bg-gray-500 hover:bg-gray-700 text-white font-bold py-2 px-4 rounded">
                    Light 3 Off
                </button>
            </div>
            <div class="p-10 border w-96 flex flex-col space-y-5">
                <img  class="w-20" :src="imgShow == true ? allImg.src : allImg.src2" alt="">
                <img  class="w-20" src="//img.icons8.com/?size=512&id=12244&format=png" alt="">
                <img  class="w-20" src="//img.icons8.com/?size=512&id=75&format=png" alt="">
            </div>
        </div>
    </section>
</template>

<style scoped></style>