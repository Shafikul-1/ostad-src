<script setup>
const toogleFastHead = 'Chamber reached do he nothing be?'
const toogleP = 'Our asked sex point her she seems. New plenty she horses parish design you. Stuff sight equal of my woody. Him children bringing goodness suitable she entirely put far daughter'
const toogleSecondHead = 'Stuff sight equal of my woody?'
const toogleThredHead = 'Amounted repeated as believed in confined?'
const toogleFourHead = 'In am do giving to afford parish settle easily garret?'

const none = 'd-none'
const clickShow1 =()=>{
    document.querySelector('.fastclick').classList.replace('d-none', 'd-block')
}
const clickShow2 =()=>{
    document.querySelector('.secondClick').classList.replace('d-none', 'd-block')
}
const clickShow3 =()=>{
    document.querySelector('.thredClick').classList.replace('d-none', 'd-block')
}
const clickShow4 =()=>{
    document.querySelector('.fourClick').classList.replace('d-none', 'd-block')
}

const container = 'container'
const row = 'row'
const colmd12 = 'col-md-12'
const colmd2 = 'col-md-2'
const colmd8 = 'col-md-8'
const center ='text-center';

</script>
<template>
<section>
        <div :class="container">
            <div :class="row">
                <div :class="colmd12">
                    <div class="row mb-4">
                        <div :class="colmd2"></div>
                        <div :class="colmd8">
                            <h1 :class="[center, heaingFontSize]" class="mt-5 mb-4">FAQ</h1>
                           <div class="fast">
                                <h3 @click="clickShow1()">{{ toogleFastHead }}</h3>
                                <p :class="none" class="fastclick ">{{ toogleP }}</p>
                            </div>
                            <div class="fast">
                                <h3 @click="clickShow2()">{{ toogleSecondHead }}</h3>
                                <p :class="none" class="secondClick">{{ toogleP }}</p>
                            </div>
                            <div class="fast">
                                <h3 @click="clickShow3()" >{{ toogleThredHead }}</h3>
                                <p :class="none" class="thredClick">{{ toogleP }}</p>
                            </div>
                             <div class="fast">
                                <h3 @click="clickShow4()">{{ toogleFourHead }}</h3>
                                <p :class="none" class="fourClick">{{ toogleP }}</p>
                            </div>
                            
                        </div>
                        <div :class="colmd2"></div>
                    </div>
                </div>
            </div>
        </div>
    </section>
</template>
<style scoped></style>