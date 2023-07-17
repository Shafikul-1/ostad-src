<script setup>
const container = 'container'
const row = 'row'
const colmd12 = 'col-md-12'
const colmd6 = 'col-md-6'
const top5 = 'mt-5'
const capitalize = 'text-capitalize'
const center ='text-center';
const cardhead = 'fs-3 font fw-bold'
const aboutCard = 'margin: 100px 0'
const aboutus = 'About us'
const aboutHeading = 'smart application services'
const aboutP = 'Ye am depending propriety sweetness distrusts belonging collected. Smiling mention he in thought equally musical. Wisdom new and valley answer. Contented it so is discourse recommend. Man its upon him call mile. An pasture he himself believe ferrars besides cottage.'
const aboutBtn = 'learn more'
const aboutSecondHead = 'What app can do to your Appliences?'
const aboutThredHead = 'Control Electric Appliences'


</script>
<template>
     <section>
        <div :class="container">
            <div class="row mb-5">
                <div :class="colmd12">
                    <h1 :class="[heaingFontSize, center]">{{ aboutus }}</h1>
                </div>
            </div>
            <div :class="[row,top5]" >
                <div :class="[colmd6, center]" >
                    <img src="../img/temprature.png" alt="" :class="center">
                </div>
                <div :class="colmd6">
                   <div :style="aboutCard ">
                    <h2 :class="[cardhead, capitalize]">{{ aboutHeading }}</h2>
                    <p>{{ aboutP }}</p>
                    <button class="myBtn">{{ aboutBtn }}</button>
                   </div>
                </div>
            </div>
            <div :class="[row, top5]">
                <div :class="colmd6">
                   <div :style="aboutCard ">
                    <h2  :class="[cardhead, capitalize]">{{ aboutSecondHead }}</h2>
                    <p>{{ aboutP }}</p>
                    <button class="myBtn ">{{ aboutBtn }}</button>
                   </div>
                </div>
                <div :class="[colmd6, center]" >
                    <img src="../img/application.png" alt="" :class="center">
                </div>
            </div>
            <div :class="[row, top5]" >
                <div :class="[colmd6, center]">
                    <img src="../img/electro.png" alt="" :class="center">
                </div>
                <div :class="colmd6">
                  <div :style="aboutCard ">
                    <h2  :class="[cardhead,capitalize]">{{ aboutThredHead }}</h2>
                    <p>{{ aboutP }}</p>
                    <button class="myBtn ">{{ aboutBtn }}</button>    
                  </div>           
                </div>
            </div>
        </div>
    </section>
</template>
<style scoped></style>