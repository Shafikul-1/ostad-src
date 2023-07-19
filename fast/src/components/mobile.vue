<script setup>
const googleimg = 'https://github.com/Shafikul-1/ostad-src/blob/fast-project/fast/src/img/google%20play.png?raw=true'
const appImg = 'https://github.com/Shafikul-1/ostad-src/blob/fast-project/fast/src/img/app%20store.png?raw=true'
const download = 'Download App'
const downloadP = 'Wisdom new and valley answer. Contented it so is discourse recommend. Man its upon him call mile. An pasture he himself believe ferrars besides cottage.'
const aboutCard = 'margin: 100px 0'
const heaingFontSize =  'fs-1 fw-bold'
const container = 'container'
const row = 'row'
const colmd6 = 'col-md-6'
const center ='text-center';
const maxWidth = 'max-width: 100%'

</script>
<template>
    <section>
        <div :class="container">
            <div :class="row">
                <div :class="colmd6"> 
                  <div :style="aboutCard">
                    <h1 :class="heaingFontSize"> {{ download }} </h1>
                    <p>{{ downloadP }}</p>
                    <div class="d-flex">
                        <img :src="appImg" alt="" :style="maxWidth">
                        <img :src="googleimg" alt="" :style="maxWidth">
                    </div>
                  </div>
                  
                </div>
                <div :class="colmd6"> 
                   <div :class="center">
                        <img src="../img/download.png" alt="download">
                   </div>
                </div>
            </div>
        </div>
    </section>
</template>
<style scoped></style>