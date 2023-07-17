<script setup>
import navbar from './components/navbar.vue';
import secondpart from './components/secondpart.vue'
import about from './components/about.vue';
//Css And Class 
const container = 'container'
const row = 'row'
const colmd12 = 'col-md-12'
const colmd2 = 'col-md-2'
const colmd8 = 'col-md-8'
const colmd6 = 'col-md-6'
const capitalize = 'text-capitalize'
const center ='text-center';
const maxWidth = 'max-width: 100%'

const manicon = 'https://cdn-icons-png.flaticon.com/512/4128/4128176.png'
const heaingFontSize =  'fs-1 fw-bold'





const top5 = 'mt-5'

const clinetimg = 'background: white; margin: 0 32px 0 0; box-shadow: 0 2px 1px 0 gray; border-radius: 6px; padding: 23px; mt-3'
const testomonialicon = 'width: 40px; height:40px; margin: 18px 0'
const man = ' margin: 11px 0px -14px 20px;'
const footerlink = 'text-decoration-none text-capitalize text-black'
const footerhead = 'fs-4 font-bold mt-5 text-uppercase'
const aboutCard = 'margin: 100px 0'
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

//All Content Start


const client = 'our clients'
const clientP = 'Wisdom new and valley answer. Contented it so is discourse recommend. Man its upon him call mile. An pasture he himself believe ferrars besides cottage.'
const Testimonials = 'Testimonials'
const testomonialP = 'Wisdom new and valley answer. Contented it so is discourse recommend. Man its upon him call mile. An pasture he himself believe ferrars besides cottage.'

const toogleFastHead = 'Chamber reached do he nothing be?'
const toogleP = 'Our asked sex point her she seems. New plenty she horses parish design you. Stuff sight equal of my woody. Him children bringing goodness suitable she entirely put far daughter'
const toogleSecondHead = 'Stuff sight equal of my woody?'
const toogleThredHead = 'Amounted repeated as believed in confined?'
const toogleFourHead = 'In am do giving to afford parish settle easily garret?'
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
const testomonialP2 = 'our company, we do ongoing research with our target audience. This includes 30-45 minute phone interviews. It was difficult to conduct the interview, really listen, and ask good follow up questions'
const testomonialManInfo = 'Product designer - Besnik'
const testomnialManName = 'Custom IT Solutions Firm'


const carosulP = 'Far far away, behind the word mountains, far from the countries Vokalia and Consonantia.'
const carouslFastHead = 'Grow Your Business'
const carouslSecondHead = 'Build Products'
const carouslThredHead = 'Success Every Day'
const carosulFourHead = 'Bring Ideas to Life'

const businessImg = 'https://preview.colorlib.com/theme/launch/images/dashboard.jpg'
const googleimg = 'https://github.com/Shafikul-1/ostad-src/blob/fast-project/fast/src/img/google%20play.png?raw=true'
const appImg = 'https://github.com/Shafikul-1/ostad-src/blob/fast-project/fast/src/img/app%20store.png?raw=true'

</script>

<template>
<navbar/>
<secondpart/>
<about/>
    <section>
        <div :class="container">
            <div :class="row">
                <div class="col-md-12 ">
                    <div :class="row">
                      <div :class="colmd2"></div>
                      <div class="col-md-8 text-center">
                        <h1 :class="[capitalize, heaingFontSize, top5]">{{ client }}</h1>
                        <p class="">{{ clientP }}</p>
                      </div>
                      <div :class="colmd2"></div>
                    </div>
                </div>
            </div>
            <div :class="row">
                <div class="col-md-1"></div>
                <div class="col-md-10 mt-4 ">
                    <div :class="row">
                        <div :class="colmd6">
                            <img src="./img/client.png" alt=""  :style="clinetimg">
                            <img src="./img/client1.png" alt=""  :style="clinetimg">
                        </div>
                        <div :class="colmd6">
                            <img src="./img/client2.png" alt=""  :style="clinetimg">
                            <img src="./img/client3.png" alt=""  :style="clinetimg">
                        </div>
                    </div>
                    <div class="row mt-4 mb-5">
                        <div :class="colmd6">
                          <img src="./img/client4.png" alt=""  :style="clinetimg">
                          <img src="./img/client5.png" alt=""  :style="clinetimg">
                        </div>
                        <div :class="colmd6">
                          <img src="./img/client6.png" alt=""  :style="clinetimg">
                          <img src="./img/client7.png" alt=""  :style="clinetimg">
                        </div>
                    </div>
                </div>
                <div class="col-md-1"></div>
            </div>
        </div>
    </section>
    <section>
        <div :class="container">
            <div :class="row">
                <div :class="colmd12">
                    <div :class="row">
                      <div :class="colmd2"></div>
                      <div class="col-md-8 mb-4">
                        <div class="text-center">
                          <h1  :class="heaingFontSize">{{ Testimonials }}</h1>
                          <p>{{ testomonialP }}</p>
                        </div>
                      </div>
                      <div :class="colmd2"></div>
                    </div>
                </div>
            </div>
        </div>
    </section>
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
    <section>
        <div :class="container">
            <div :class="row">
                <div :class="colmd6">
                    <div class="testomialCard">
                        <em>{{ testomonialP2 }}</em>
                        <div class="d-flex">
                            <img :src="manicon" alt="man" :style="testomonialicon" style="">
                            <div :style="man">
                                <h5 :class="capitalize">{{ testomnialManName }}</h5>
                                <p>{{ testomonialManInfo }}</p>
                            </div>
                        </div>
                    </div>
                </div>
                <div :class="colmd6">
                  <div class="testomialCard">
                    <em>{{ testomonialP2 }}</em>
                    <div class="d-flex">
                        <img :src="manicon" alt="man" :style="testomonialicon"  >
                        <div :style="man">
                            <h5 :class="capitalize">{{ testomnialManName }}</h5>
                            <p>{{ testomonialManInfo }}</p>
                        </div>
                    </div>
                  </div>
                </div>
            </div>
            <div :class="row">
                <div :class="colmd6">
                   <div class="testomialCard">
                    <em>{{ testomonialP2 }}</em>
                    <div class="d-flex">
                        <img :src="manicon" alt="man" :style="testomonialicon" >
                        <div :style="man">
                            <h5 :class="capitalize">{{ testomnialManName }}</h5>
                            <p>{{ testomonialManInfo }}</p>
                        </div>
                    </div>
                   </div>
                </div>
                <div :class="colmd6">
                   <div class="testomialCard">
                    <em>{{ testomonialP2 }}</em>
                    <div class="d-flex">
                        <img :src="manicon" alt="man" :style="testomonialicon" >
                        <div :style="man">
                            <h5 :class="capitalize">{{ testomnialManName }}</h5>
                            <p>{{ testomonialManInfo }}</p>
                        </div>
                    </div>
                   </div>
                </div>
            </div>
        </div>
    </section>
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
