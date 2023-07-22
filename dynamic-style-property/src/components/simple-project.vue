<script setup>
import { reactive, computed } from 'vue'
const allStyle = reactive({
      perspective: 100,
      rotateX:0,
      rotateY:0,
      rotateZ:0,
      width:30,
      height:50
})

const checking = computed(()=>{
  return {
    transform: `
    perspective(${allStyle.perspective}px)
    rotateX(${allStyle.rotateX}deg)
    rotateY(${allStyle.rotateY}deg)
    rotateZ(${allStyle.rotateZ}deg)
    `,
    width:` ${allStyle.width}px`,
    height:` ${allStyle.height}px`
  }
})


function resetFn(){
  allStyle.perspective = 100
  allStyle.rotateX = 0
  allStyle.rotateY = 0
  allStyle.rotateZ = 0
  allStyle.width = 30
  allStyle.height = 50
}
</script>
<template>
  <h1 class="font-bold text-center mt-4 text-3xl font-serif">Pratice Project</h1>
  <div class="flex gap-10 mt-10">
    <div class="w-1/2">

      <div class="element">
        <label for="" >Width : {{ allStyle.width }}px</label>
        <input type="range" name="0" min="" max="400" id=""  v-model="allStyle.width">
      </div>

      <div class="element">
        <label for="" >Height : {{ allStyle.height }}px</label>
        <input type="range" name="0" min="" max="400" id=""  v-model="allStyle.height">
      </div>

      <div class="element">
        <label for="" >Perspective : {{ allStyle.perspective }}px</label>
        <input type="range" name="0" min="" max="400" id=""  v-model="allStyle.perspective">
      </div>

       <div class="element">
        <label for="" >RotateX : {{ allStyle.rotateX }}deg</label>
        <input type="range" name="" min="-360" max="360" id="" v-model="allStyle.rotateX">
      </div>

       <div class="element">
        <label for="" >RotateY : {{ allStyle.rotateY }}deg</label>
        <input type="range" name="" min="-360" max="360" id="" v-model="allStyle.rotateY">
      </div>

       <div class="element">
        <label for="" >RotateZ : {{ allStyle.rotateZ }}deg</label>
        <input type="range" name="" min="-360" max="360" id="" v-model="allStyle.rotateZ">
      </div>
    </div>
    <div class="border-4 border-red-700 p-10 h-52 w-52 flex justify-center">
      <div class=" w-24 h-24 bg-slate-300" :style="checking"> </div>
    </div>
  </div>
  <button @click="resetFn" class="w-32 ml-20 text-2xl font-bold capitalize border-2 border-gray-200 shadow-md shadow-indigo-300"> Reset</button>
</template>
<style scoped>
/* .fast{
  transform: rotateX('angle');
  height: 30px;
} */
</style>