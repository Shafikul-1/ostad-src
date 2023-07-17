<script setup>
const container = 'container'
const row = 'row'
const colmd4 = 'col-md-4'
const colmd2 = 'col-md-2'
const colmd8 = 'col-md-8'
const capitalize = 'text-capitalize'
const center ='text-center';
const heading = 'smart mobile application'
const herop = 'wisdom new valley answer. Contented it so is discourse recommend. Man ites upon him call mile. An pasture he himself believe'
const paragrapefontSize = 'fs-6'

const appdownload1 = `box-shadow: 0 0 3px 0 black; border-radius: 8px;`
const appdownload2 = 'border-radius: 6px; box-shadow: 0 0 5px 0 black; padding: 9px; margin: 0 14px;'

const googleimg = 'https://github.com/Shafikul-1/ostad-src/blob/fast-project/fast/src/img/google%20play.png?raw=true'
const appImg = 'https://github.com/Shafikul-1/ostad-src/blob/fast-project/fast/src/img/app%20store.png?raw=true'

</script>
<template>
     <section>
        <a href=""></a>
        <div :class="container">
            <div :class="row">
                <div :class="colmd2"></div>
                <div :class="colmd8">
                   <div class="p-3" :class="center">
                    <h1 :class="[heaingFontSize, capitalize]">{{ heading }}</h1>
                    <p :class="paragrapefontSize">{{ herop }}</p>
                   </div>
                </div>
                <div :class="colmd2"></div>
                
                <div :class="colmd2"></div>
                <div :class="[colmd8, center]" >
                    <img src="../img/fast.png" alt="" class="m-2" :style="maxWidth">
                    <img src="../img/seconf.png" alt="" class="m-2" :style="maxWidth">
                    <img src="../img/threed.png" alt="" class="m-2" :style="maxWidth">
                </div>
                <div :class="colmd2"></div>
            </div>
            <div :class="row" class="mt-5 mb-5">
                <div :class="colmd4"></div>
                <div :class="colmd4">
                    <img :src="googleimg" alt=""   :style="appdownload1">
                    <img :src="appImg" alt="" :style="appdownload2">
                </div>
                <div :class="colmd4"></div>
            </div>
        </div>
    </section>
</template>

<style scoped></style>