<script setup>
import HelloWorld from './components/HelloWorld.vue';
// import {countryName} from './data/countryName'
// // console.log(countryName);

// const countriesStartingWithB = countryName.filter((item) =>{
//   const itemcountry = item.country.toLowerCase()
//   return itemcountry.startsWith('b')
// } );
// const countriesStartingWithC = countryName.filter((item) =>{
//   const itemcountry = item.country.toLowerCase()
//   return itemcountry.startsWith('c')
// } );
// //console.log(countriesStartingWithB)
// const divStyle = 'country shadow-md shadow-indigo-400 shadow-black rounded text-center w-80 my-4 py-8'




</script>
<template>
  <HelloWorld/>
  <!-- <div class="flex">
    <div class="mx-7">
      <h4 class="text-xl my-6 font-bold">Country Name Start => B</h4>
        <div class="bg-lime-100" :class="divStyle" v-for="(country, index) in countriesStartingWithB" :key="index">
          <h4 class="font-bold text-xl">{{ country.country }}</h4>
          <code>{{ country.city }}</code>
      </div>
    </div>

  `<div class="mx-7">
    <h4 class="text-xl my-6 font-bold">Country Name Start => C</h4>
      <div class="bg-teal-200 " :class="divStyle" v-for="(country, index) in countriesStartingWithC" :key="index">
        <h4 class="font-bold text-xl">{{ country.country }}</h4>
        <code>{{ country.city }}</code>
      </div>
    </div>`
  </div> -->
</template>

<style scoped></style>