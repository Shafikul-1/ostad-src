<script setup>
import navbar from './components/navbar.vue';
import secondpart from './components/secondpart.vue'
import about from './components/about.vue';
import client from './components/client.vue';
import testomonial from './components/testomonial.vue'
import carosol from './components/carosol.vue'
import tescard from './components/tescard.vue'
import faq from './components/faq.vue'

//Css And Class 
const container = 'container'
const row = 'row'
const colmd2 = 'col-md-2'
const colmd6 = 'col-md-6'
const center ='text-center';
const maxWidth = 'max-width: 100%'


const heaingFontSize =  'fs-1 fw-bold'






const footerlink = 'text-decoration-none text-capitalize text-black'
const footerhead = 'fs-4 font-bold mt-5 text-uppercase'
const aboutCard = 'margin: 100px 0'


//All Content Start



const download = 'Download App'
const downloadP = 'Wisdom new and valley answer. Contented it so is discourse recommend. Man its upon him call mile. An pasture he himself believe ferrars besides cottage.'
const subscribe = 'Subscribe to get updated'
const subscribeP = 'At vero eos et accusamus et iusto odio dignissimos ducimus qui blanditiis praesentium voluptatum deleniti atque.'
const footerHead = 'Smart Mobile Application'
const footerP = 'Automate your entine healthcare hiring, onboadrding and Compllance eith true technology platefrom'

const footerLink1 = 'product management'
const footerLink2 = 'design / creatves'
const footerLink3 = 'education & trainging'
const footerLink4 = 'ul/ux designers'
const footerLink5 = 'About Us'
const footerLink6 = 'Partnerships'
const footerLink7 = 'Finance Experts'
const footerLink8 = 'Project Management'
const Facebook = 'Facebook'
const Twitter = 'Twitter'
const Instagram = 'Instagram'
const Linkedin = "Linkedin"
const footerHeading = 'categories'
const footerHeading2 = 'About'
const footerHeading3 = 'Follow Us'






const googleimg = 'https://github.com/Shafikul-1/ostad-src/blob/fast-project/fast/src/img/google%20play.png?raw=true'
const appImg = 'https://github.com/Shafikul-1/ostad-src/blob/fast-project/fast/src/img/app%20store.png?raw=true'

</script>

<template>
<navbar/>
<secondpart/>
<about/>
<client/>
<testomonial/>
<carosol/>
<tescard/>
<faq/>
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
                        <img src="./img/download.png" alt="download">
                   </div>
                </div>
            </div>
        </div>
    </section>
    <section>
        <div :class="container">
            <div class="row footerAge">
                <div :class="colmd2"> 
                    <img src="./img/mobile.png" :style="maxWidth" style=" height: 160px; " alt="">    
                </div>
                <div class="col-md-8 "> 
                    <h1>{{ subscribe }}</h1>
                    <p>{{ subscribeP }}</p>
                </div>
                <div :class="colmd2"> 
                    <button class="myBtn">get start</button>
                </div>
            </div>
        </div>
    </section>
    <section>
        <div :class="container">
            <div :class="row">
                <div class="col-md-3">
                    <h2 :class="footerhead">{{ footerHead }}</h2>
                    <p>{{ footerP }}</p>
                    <div class="d-flex">
                        <input type="text" placeholder="Enter Your Text here" class="footerInp">
                        <button class="myBtn" type="submit">Registar</button>
                    </div>
                </div>
                <div class="col-md-3">
                    <h3 :class="footerhead">{{ footerHeading }}</h3>
                    <ul class="list-unstyled">
                        <li><a href="#" :class="footerlink">{{ footerLink1 }}</a></li>
                        <li><a href="#" :class="footerlink">{{ footerLink2 }}</a></li>
                        <li><a href="#" :class="footerlink">{{ footerLink3 }}</a></li>
                        <li><a href="#" :class="footerlink">{{ footerLink4 }}</a></li>
                    </ul>
                </div>
                <div class="col-md-3">
                    <h3 :class="footerhead">{{ footerHeading2 }}</h3>
                    <ul class="list-unstyled text-capitalize">
                        <li><a href="#" :class="footerlink">{{ footerLink5 }} </a></li>
                        <li><a href="#" :class="footerlink">{{ footerLink6 }}</a></li>
                        <li><a href="#" :class="footerlink">{{ footerLink7 }} </a></li>
                        <li><a href="#" :class="footerlink">{{ footerLink8 }} </a></li>
                    </ul>
                </div>
                <div class="col-md-3">
                    <h3 :class="footerhead">{{ footerHeading3 }}  </h3>
                    <ul class="list-unstyled text-capitalize">
                        <li><a href="#" :class="footerlink">{{ Facebook }}</a></li>
                        <li><a href="#" :class="footerlink">{{ Twitter }}</a></li>
                        <li><a href="#" :class="footerlink">{{ Instagram }}</a></li>
                        <li><a href="#" :class="footerlink">{{ Linkedin }}</a></li>
                    </ul>
                </div>
            </div>
        </div>
    </section>
    <br/><br/>
</template>

<style scoped>

</style>
