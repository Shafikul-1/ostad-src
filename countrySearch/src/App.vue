<script setup>
 import { ref, reactive } from 'vue'
 const countery = reactive([
    {
        commonName: 'All Country List',
        officialName: 'All Country List',
        independent: 'All',
        status: 'officially-assigned',
        capital: 'All',
        languages: 'english',
        flag: '',
        // googleMaps:	"https://goo.gl/maps/Re9ePMjwP1sFCBFA6",
        flags: 'https://cdn.pixabay.com/photo/2017/11/12/22/50/exhibition-2944064_1280.jpg',
        alt: "The flag of North Korea is composed of three horizontal bands — a large central white-edged red band, and a blue band above and beneath the red band. On the hoist side of the red band is a red five-pointed star within a white circle.",
        capitalInfo : '50.83'
    }
 ])

 function countryName(list = 'all')  {
    countery.length = 0;
    let url = 'https://restcountries.com/v3.1/all'
    fetch (url)
    .then(response => response.json())
    .then(result => {
        if(list == 'all'){
            result.forEach(countryEle => {
            countery.push({
                commonName: countryEle.name.common,
                officialName: countryEle.name.official,
                independent: countryEle.independent,
                status: countryEle.status,
                flag : countryEle.flag,
                flags: countryEle.flags.png,
                alt: countryEle.flags.alt,
                // capital: countryEle.capital[0]
            })
            console.log(result)
        });
        }else{
            result.filter(c => c.name.common.startsWith(list.toUpperCase())).forEach(countryEle => {
                countery.push({
                    commonName: countryEle.name.common,
                    officialName: countryEle.name.official,
                    independent: countryEle.independent,
                    status: countryEle.status,
                    flag : countryEle.flag,
                    flags: countryEle.flags.png,
                    alt: countryEle.flags.alt,
                })
            });
        }
    })
 }



    const inputValue = ref('')
</script>
<template>

    <div class="imputSec flex mx-auto my-5">
        <div class="inputSection w-10/12">
            <input v-model="inputValue" class="  py-3 mr-5 pl-5 rounded shadow-md shadow-indigo-300 focus:outline-none" type="text" placeholder="Ener your Place Search ..." >
            <p class="font-bold text-xl mt-4">Your Search Text : <span class="font-normal"> "{{ inputValue }} " </span></p>
        </div>
        <button class="h-[3.4rem] rounded bg-indigo-200 hover:shadow-xl shadow-indigo-500 hover:bg-white w-1/6 hover:shadow-indigo-500 hover:rounded-xl hover:transition-all shadow-md h"  @click="countryName(inputValue)">Check the Result</button>
    </div>
    <div class="contentPart w-[24rem] h-[25rem] overflow-auto shadow-md my-6 hover:shadow-2xl hover:shadow-indigo-400 hover:transition-shadow duration-300 hover:bg-white bg-indigo-200  rounded-md p-5" v-for="(country, index) in countery" :key="index">
        <img :src="country.flags" alt="">
        <h2 class="my-2 font-semibold">Country Common Name : <span class=" text-red-500 font-bold">{{ country.commonName }} </span></h2>
        <h3 class="my-2 font-semibold">Country Official Name : <span class="font-normal">{{ country.officialName }} </span></h3>
        <p class="my-2 font-semibold">Independent : <span class="font-normal">{{ country.independent }} </span></p>
        <p class="my-2 font-semibold">Status : <span class="font-normal">{{ country.status }} </span></p>
        <p class="my-2 font-semibold">Capital : <span class="font-normal">{{ country.capital }} </span></p>
        <p class="my-2 font-semibold">Description : <span class="font-normal">{{ country.alt }} </span></p>
        <!-- <iframe :src="country.googleMaps" width="100" height="100" style="border:0;" allowfullscreen="" loading="lazy" referrerpolicy="no-referrer-when-downgrade"></iframe> -->
    </div>
</template>

<style scoped></style>