<script setup>
//Css And Class 
const container = 'container'
const row = 'row'
const colmd12 = 'col-md-12'
const colmd4 = 'col-md-4'
const colmd2 = 'col-md-2'
const colmd8 = 'col-md-8'
const colmd6 = 'col-md-6'
const navbar = 'navbar navbar-expand-lg navbar-light'
const navitem = 'nav-item'
const navlink = 'nav-link'
const manicon = 'https://cdn-icons-png.flaticon.com/512/4128/4128176.png'
const heaingFontSize =  'fs-1 fw-bold'
const paragrapefontSize = 'fs-6'
const marginSmart = 'margin : 12px 0 0 0'
const appdownload1 = `box-shadow: 0 0 3px 0 black; border-radius: 8px;`
const appdownload2 = 'border-radius: 6px; box-shadow: 0 0 5px 0 black; padding: 9px; margin: 0 14px;'
const maxWidth = 'max-width: 100%'
const center ='text-center';
const cardhead = 'fs-3 font fw-bold'
const top5 = 'mt-5'
const capitalize = 'text-capitalize'
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
const home = 'Home'
const heading = 'smart mobile application'
const herop = 'wisdom new valley answer. Contented it so is discourse recommend. Man ites upon him call mile. An pasture he himself believe'
const aboutus = 'About us'
const aboutHeading = 'smart application services'
const aboutP = 'Ye am depending propriety sweetness distrusts belonging collected. Smiling mention he in thought equally musical. Wisdom new and valley answer. Contented it so is discourse recommend. Man its upon him call mile. An pasture he himself believe ferrars besides cottage.'
const aboutBtn = 'learn more'
const aboutSecondHead = 'What app can do to your Appliences?'
const aboutThredHead = 'Control Electric Appliences'
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
    <section>
        <div :class="container">
            <div :class="row">
                <div :class="colmd4">
                    <nav :class="navbar">
                        <div class="container-fluid">
                          <a class="navbar-brand" href="#"></a>
                          <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarNav" aria-controls="navbarNav" aria-expanded="false" aria-label="Toggle navigation">
                            <span class="navbar-toggler-icon"></span>
                          </button>
                          <div class="collapse navbar-collapse" id="navbarNav">
                            <ul class="navbar-nav">
                              <li :class="navitem">
                                <a class=" active" aria-current="page" href="#" :class="navlink">{{ home }}</a>
                              </li>
                              <li :class="navitem">
                                <a :class="navlink" href="#">About </a>
                              </li>
                              <li :class="navitem">
                                <a :class="navlink" href="#">Pricing</a>
                              </li>
                              <li :class="navitem">
                                <a class="nav-link " href="#" >Contact</a>
                              </li>
                               <li :class="navitem">
                                <a class="nav-link " href="#" >Blog</a>
                              </li>
                            </ul>
                          </div>
                        </div>
                    </nav>
                </div>
                <div :class="colmd4">
                    <h3 :class="capitalize" :style="marginSmart">smart application</h3>
                </div>
                <div :class="colmd4" :style="marginSmart">
                    <button class="myBtn">login</button>
                    <button class="myBtn">sign up</button>
                </div>
            </div>
        </div>
    </section>
    <section>
        <div :class="container">
            <div :class="row">
                <div :class="colmd2"></div>
                <div :class="colmd8">
                   <div class="p-3">
                    <h1 :class="[heaingFontSize, capitalize]">{{ heading }}</h1>
                    <p :class="paragrapefontSize">{{ herop }}</p>
                   </div>
                </div>
                <div :class="colmd2"></div>
                
                <div :class="colmd2"></div>
                <div :class="[colmd8, center]" >
                    <img src="./img/fast.png" alt="" class="m-2" :style="maxWidth">
                    <img src="./img/seconf.png" alt="" class="m-2" :style="maxWidth">
                    <img src="./img/threed.png" alt="" class="m-2" :style="maxWidth">
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
    <section>
        <div :class="container">
            <div class="row mb-5">
                <div :class="colmd12">
                    <h1 :class="[heaingFontSize, center]">{{ aboutus }}</h1>
                </div>
            </div>
            <div :class="[row,top5]" >
                <div :class="[colmd6, center]" >
                    <img src="./img/temprature.png" alt="" :class="center">
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
                    <img src="./img/application.png" alt="" :class="center">
                </div>
            </div>
            <div :class="[row, top5]" >
                <div :class="[colmd6, center]">
                    <img src="./img/electro.png" alt="" :class="center">
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
.myBtn{
  border: 2px double gray;
  margin:0 2px ;
  padding: 5px 25px;
  border-radius: 6px;
  text-transform: capitalize;
  font-size: 15px;
  font-weight: 600;
  cursor: pointer;
  outline: none;
  background: #000000;
  color: white;
  box-shadow: 0 1px 3px 0 rgb(199, 139, 209);
}
.myBtn:hover{
  transition: all .2s;
  color: black;
  box-shadow: 0 0 5px 0 black;
  background: #ffffff;
}
.testomialCard{
    background: rgba(222, 222, 222, 0.49);
    border-radius: 5px;
    box-shadow: 0 1px 3px 0 rgb(123, 123, 123);
    padding: 15px;
    margin: 6px 0;
}
.testomialCard:hover{
       background: rgba(0, 0, 0, 0.49);
       color: white;
}
.footerAge{
    color: white;
    background: #1E5AF9;
    padding: 56px 0 0 0;
    margin: 10px 0 0 0;
    box-shadow: 0 1px 3px 0 black;
    border-radius: 6px;
}
.footerInp{
    border: 1px solid gray;
    outline: none;
}
.fast{
    background: white;
    border-radius: 6px;
    box-shadow: 0 1px 2px 0 black;
    padding: 18px;
    transition:all .5s;
    margin: 16px 0px;
    cursor: pointer;
}
.fast h3{
    font-size: 20px;
}
.fast:hover{
    background: rgb(148, 124, 235);
    color:white;
}
@media screen and (max-width: 767px) {
    img{
        margin-top: 15px !important;
    }
    .footerAge{
        padding: 10px 0 10px 0;
    }
}
.carosul{
    background: #efefef45;
    padding: 10px;
    margin: 10px 0;
    transition: .3s;
    cursor: pointer;
    border-radius: 8px;
}
.carosul:hover{
    background: #ffffff;  
    box-shadow: 0 1px 2px 0 black;
    border-right-style: 2px solid rgb(178, 97, 243);
}
</style>
