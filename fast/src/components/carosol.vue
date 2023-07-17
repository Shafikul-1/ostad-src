<script setup>
const container = 'container'
const row = 'row'
const colmd6 = 'col-md-6'
const maxWidth = 'max-width: 100%'
const carosulP = 'Far far away, behind the word mountains, far from the countries Vokalia and Consonantia.'
const carouslFastHead = 'Grow Your Business'
const carouslSecondHead = 'Build Products'
const carouslThredHead = 'Success Every Day'
const carosulFourHead = 'Bring Ideas to Life'
const businessImg = 'https://preview.colorlib.com/theme/launch/images/dashboard.jpg'
</script>
<template>
    <section>
        <div :class="container">
            <div :class="row">
                <div :class="colmd6"> 
                   <div class="post">
                    <div class="carosulimgal">
                        <img class="fastimg" :class="[fastimg]" :style="maxWidth" :src="businessImg"  alt="">
                        <!-- <img class="fastimg" :class="[fastimg]" :style="maxWidth" :src="businessImg"  alt="">
                        <img class="fastimg" :class="[fastimg]" :style="maxWidth" :src="businessImg"  alt="">
                        <img class="fastimg" :class="[fastimg]" :style="maxWidth" :src="businessImg"  alt=""> -->
                    </div>
                   </div>
                </div>
                <div :class="colmd6"> 
                    <div class="carosul">
                        <h4>{{ carouslFastHead }}</h4>
                        <p>{{ carosulP }}</p>
                    </div>
                     <div class="carosul">
                        <h4>{{ carouslSecondHead }}</h4>
                        <p>{{ carosulP }}</p>
                    </div>
                       <div class="carosul">
                        <h4>{{ carouslThredHead }}</h4>
                        <p>{{ carosulP }}</p>
                    </div>
                       <div class="carosul">
                        <h4>{{ carosulFourHead }}</h4>
                        <p>{{ carosulP }}</p>
                    </div>
                    
                </div>
            </div>
        </div>
    </section>
</template>
<style scoped></style>