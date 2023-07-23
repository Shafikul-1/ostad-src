<script setup>
import { ref } from 'vue';
const currentIndex = ref(0);

function prevImg() {
  currentIndex.value = (currentIndex.value - 1 + images.length) % images.length;
}

function nextImg() {
  if(currentIndex.value == (images.length - 1)){
    currentIndex.value = 0;
  }else{
    currentIndex.value++
  }
}

const images = [
    {
      url: 'https://cdn.pixabay.com/photo/2023/07/17/13/44/prairie-dog-8132681_1280.jpg',
      alt: 'Prairie Dog',
      title: '',
      paragrape:'Lorem ipsum dolor sit amet, consectetur adipisicing elit. Molestias, dolore. Odio repellendus',
    },
    {
      url: 'https://cdn.pixabay.com/photo/2023/07/18/15/17/large-headed-knapweed-8135055_1280.jpg',
      alt: 'Large Headed Knapweed',
      title: '',
      paragrape:'Lorem ipsum dolor sit amet, consectetur adipisicing elit. Molestias, dolore. Odio repellendus',
    },
    {
      url: 'https://cdn.pixabay.com/photo/2015/04/23/22/00/tree-736885_1280.jpg',
      alt: 'Large Headed Knapweed',
      title: '',
      paragrape:'Lorem ipsum dolor sit amet, consectetur adipisicing elit. Molestias, dolore. Odio repellendus',
    },
    {
      url:  'https://cdn.pixabay.com/photo/2015/12/01/20/28/road-1072821_1280.jpg',
      alt: 'Large Headed Knapweed',
      title: '',
      paragrape:'Lorem ipsum dolor sit amet, consectetur adipisicing elit. Molestias, dolore. Odio repellendus',
    },
    {
      url: 'https://cdn.pixabay.com/photo/2016/01/08/11/57/butterflies-1127666_1280.jpg',
      alt: 'Large Headed Knapweed',
      title: '',
      paragrape:'Lorem ipsum dolor sit amet, consectetur adipisicing elit. Molestias, dolore. Odio repellendus',
    },
    {
      url: 'https://cdn.pixabay.com/photo/2012/06/19/10/32/owl-50267_1280.jpg',
      alt: 'Large Headed Knapweed',
      title: '',
      paragrape:'Lorem ipsum dolor sit amet, consectetur adipisicing elit. Molestias, dolore. Odio repellendus',
    },
    
  ];
  
</script>

<template>
  
<h1 class="text-2xl text-center font-bold my-7">The Slider Carosul</h1>
  <div>
    <div class="mx-auto flex w-1/2">
      <div class="btn w-1/6">
        <button @click="prevImg" class="mt-20 ml-[-27px] border-2 border-gray-300 rounded-md shadow-indigo-300 shadow-md">Prev</button>
      </div>

      <div class="text-center bg-slate-100 relative h-[20rem] overflow-hidden">
        <div v-for="(image, index) in images" :key="index" class="absolute w-full h-full ">
          <div class="">
            <img :src="image.url" class="sobing w-full h-full" alt="" v-show="index === currentIndex">
          </div>

          <div class="translate-y-[-9rem] bg-[#8080807d] text-white p-5">
            <h4 class="font-bold text-3xl capitalize">{{ image.alt }}</h4>
            <p>{{ image.paragrape }}</p>
          </div>
        </div>
      </div>

      <div class="btn w-1/6">
        <button @click="nextImg" class="mt-20 ml-[40px] border-2 border-gray-300 rounded-md shadow-indigo-300 shadow-md">Next</button>
      </div>
    </div>
  </div>

</template>

<style scoped>

</style>