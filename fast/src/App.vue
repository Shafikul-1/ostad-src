<script setup>
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
</script>

<template>
    <section>
        <div class="container">
            <div class="row">
                <div class="col-md-4">
                    <nav class="navbar navbar-expand-lg navbar-light">
                        <div class="container-fluid">
                          <a class="navbar-brand" href="#"></a>
                          <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarNav" aria-controls="navbarNav" aria-expanded="false" aria-label="Toggle navigation">
                            <span class="navbar-toggler-icon"></span>
                          </button>
                          <div class="collapse navbar-collapse" id="navbarNav">
                            <ul class="navbar-nav">
                              <li class="nav-item">
                                <a class="nav-link active" aria-current="page" href="#">Home</a>
                              </li>
                              <li class="nav-item">
                                <a class="nav-link" href="#">About </a>
                              </li>
                              <li class="nav-item">
                                <a class="nav-link" href="#">Pricing</a>
                              </li>
                              <li class="nav-item">
                                <a class="nav-link " href="#" >Contact</a>
                              </li>
                               <li class="nav-item">
                                <a class="nav-link " href="#" >Blog</a>
                              </li>
                            </ul>
                          </div>
                        </div>
                    </nav>
                </div>
                <div class="col-md-4">
                    <h3 class="text-capitalize" :style="marginSmart">smart application</h3>
                </div>
                <div class="col-md-4" :style="marginSmart">
                    <button class="myBtn">login</button>
                    <button class="myBtn">sign up</button>
                </div>
            </div>
        </div>
    </section>
    <section>
        <div class="container">
            <div class="row">
                <div class="col-md-2"></div>
                <div class="col-md-8 text-center ">
                   <div class="p-3">
                    <h1 class="text-capitalize" :class="heaingFontSize">smart mobile application</h1>
                    <p :class="paragrapefontSize">wisdom new valley answer. Contented it so is discourse recommend. Man ites upon him call mile. An pasture he himself believe</p>
                  
                   </div>
                </div>
                <div class="col-md-2"></div>
                
                <div class="col-md-2"></div>
                <div class="col-md-8" :class="center">
                    <img src="./img/fast.png" alt="" class="m-2" :style="maxWidth">
                    <img src="./img/seconf.png" alt="" class="m-2" :style="maxWidth">
                    <img src="./img/threed.png" alt="" class="m-2" :style="maxWidth">
                </div>
                <div class="col-md-2"></div>
            </div>
            <div class="row mt-5 mb-5">
                <div class="col-md-4"></div>
                <div class="col-md-4">
                    <img src="./img/app store.png" alt=""   :style="appdownload1">
                    <img src="./img/google play.png" alt="" :style="appdownload2">
                </div>
                <div class="col-md-4"></div>
            </div>
        </div>
    </section>

    <section>
        <div class="container">
            <div class="row mb-5">
                <div class="col-md-12">
                    <h1 :class="[heaingFontSize, center]">About us</h1>
                </div>
            </div>
            <div class="row" :class="top5">
                <div class="col-md-6" :class="center">
                    <img src="./img/temprature.png" alt="" :class="center">
                </div>
                <div class="col-md-6">
                   <div :style="aboutCard ">
                    <h2 :class="[cardhead, capitalize]">smart application services</h2>
                    <p>Ye am depending propriety sweetness distrusts belonging collected. Smiling mention he in thought equally musical. Wisdom new and valley answer. Contented it so is discourse recommend. Man its upon him call mile. An pasture he himself believe ferrars besides cottage.</p>
                    <button class="myBtn">learn more</button>
                   </div>
                </div>
            </div>
            <div class="row" :class="top5">
                <div class="col-md-6">
                   <div :style="aboutCard ">
                    <h2  :class="[cardhead, capitalize]">What app can do to your Appliences?</h2>
                    <p>Ye am depending propriety sweetness distrusts belonging collected. Smiling mention he in thought equally musical. Wisdom new and valley answer. Contented it so is discourse recommend. Man its upon him call mile. An pasture he himself believe ferrars besides cottage.</p>
                    <button class="myBtn ">learn more</button>
                   </div>
                </div>
                <div class="col-md-6" :class="center">
                    <img src="./img/application.png" alt="" :class="center">
                </div>
            </div>
            <div class="row" :class="top5">
                <div class="col-md-6" :class="center">
                    <img src="./img/electro.png" alt="" :class="center">
                </div>
                <div class="col-md-6">
                  <div :style="aboutCard ">
                    <h2  :class="[cardhead,capitalize]">Control Electric Appliences</h2>
                    <p>Ye am depending propriety sweetness distrusts belonging collected. Smiling mention he in thought equally musical. Wisdom new and valley answer. Contented it so is discourse recommend. Man its upon him call mile. An pasture he himself believe ferrars besides cottage.</p>
                    <button class="myBtn ">learn more</button>    
                  </div>           
                </div>
            </div>
        </div>
    </section>
    <section>
        <div class="container">
            <div class="row">
                <div class="col-md-12 ">
                    <div class="row">
                      <div class="col-md-2"></div>
                      <div class="col-md-8 text-center">
                        <h1 :class="[capitalize, heaingFontSize, top5]">our clients</h1>
                        <p class="">Wisdom new and valley answer. Contented it so is discourse recommend. Man its upon him call mile. An pasture he himself believe ferrars besides cottage.</p>
                      </div>
                      <div class="col-md-2"></div>
                    </div>
                </div>
            </div>
            <div class="row">
                <div class="col-md-1"></div>
                <div class="col-md-10 mt-4 ">
                    <div class="row">
                        <div class="col-md-6">
                            <img src="./img/client.png" alt=""  :style="clinetimg">
                            <img src="./img/client1.png" alt=""  :style="clinetimg">
                        </div>
                        <div class="col-md-6">
                            <img src="./img/client2.png" alt=""  :style="clinetimg">
                            <img src="./img/client3.png" alt=""  :style="clinetimg">
                        </div>
                    </div>
                    <div class="row mt-4 mb-5">
                        <div class="col-md-6">
                          <img src="./img/client4.png" alt=""  :style="clinetimg">
                          <img src="./img/client5.png" alt=""  :style="clinetimg">
                        </div>
                        <div class="col-md-6">
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
        <div class="container">
            <div class="row">
                <div class="col-md-12">
                    <div class="row">
                      <div class="col-md-2"></div>
                      <div class="col-md-8 mb-4">
                        <div class="text-center">
                          <h1  :class="heaingFontSize">Testimonials</h1>
                          <p>Wisdom new and valley answer. Contented it so is discourse recommend. Man its upon him call mile. An pasture he himself believe ferrars besides cottage.</p>
                        </div>
                      </div>
                      <div class="col-md-2"></div>
                    </div>
                </div>
            </div>
        </div>
    </section>
    <section>
        <div class="container">
            <div class="row">
                <div class="col-md-6">
                    <div class="testomialCard">
                        <em>our company, we do ongoing research with our target audience. This includes 30-45 minute phone interviews. It was difficult to conduct the interview, really listen, and ask good follow up questions</em>
                        <div class="d-flex">
                            <img :src="manicon" alt="man" :style="testomonialicon" style="">
                            <div :style="man">
                                <h5 class="text-capitalize">cham</h5>
                                <p>Product designer - Besnik</p>
                            </div>
                        </div>
                    </div>
                </div>
                <div class="col-md-6">
                  <div class="testomialCard">
                    <em>We meet new clients and more often than not establish long-term business relationships, all through Guru. The flexibility in how projects can be structured</em>
                    <div class="d-flex">
                        <img :src="manicon" alt="man" :style="testomonialicon"  >
                        <div :style="man">
                            <h5 class="text-capitalize">Scopic Software</h5>
                            <p>Custom IT Solutions Firm</p>
                        </div>
                    </div>
                  </div>
                </div>
            </div>
            <div class="row">
                <div class="col-md-6">
                   <div class="testomialCard">
                    <em>our company, we do ongoing research with our target audience. This includes 30-45 minute phone interviews. It was difficult to conduct the interview, really listen, and ask good follow up questions</em>
                    <div class="d-flex">
                        <img :src="manicon" alt="man" :style="testomonialicon" >
                        <div :style="man">
                            <h5 class="text-capitalize">cham</h5>
                            <p>Product designer - Besnik</p>
                        </div>
                    </div>
                   </div>
                </div>
                <div class="col-md-6">
                   <div class="testomialCard">
                    <em>We meet new clients and more often than not establish long-term business relationships, all through Guru. The flexibility in how projects can be structured</em>
                    <div class="d-flex">
                        <img :src="manicon" alt="man" :style="testomonialicon" >
                        <div :style="man">
                            <h5 class="text-capitalize">Scopic Software</h5>
                            <p>Custom IT Solutions Firm</p>
                        </div>
                    </div>
                   </div>
                </div>
            </div>
        </div>
    </section>
    <section>
        <div class="container">
            <div class="row">
                <div class="col-md-12">
                    <div class="row">
                        <div class="col-md-2"></div>
                        <div class="col-md-8">
                           <div class="fast">
                                <h3>Chamber reached do he nothing be?</h3>
                                <p>Our asked sex point her she seems. New plenty she horses parish design you. Stuff sight equal of my woody. Him children bringing goodness suitable she entirely put far daughter.</p>
                            </div>
                            <div class="fast">
                                <h3>Stuff sight equal of my woody?</h3>
                                <p>Our asked sex point her she seems. New plenty she horses parish design you. Stuff sight equal of my woody. Him children bringing goodness suitable she entirely put far daughter.</p>
                            </div>
                            <div class="fast">
                                <h3>Amounted repeated as believed in confined?</h3>
                                <p>Our asked sex point her she seems. New plenty she horses parish design you. Stuff sight equal of my woody. Him children bringing goodness suitable she entirely put far daughter.</p>
                            </div>
                             <div class="fast">
                                <h3>In am do giving to afford parish settle easily garret?</h3>
                                <p>Our asked sex point her she seems. New plenty she horses parish design you. Stuff sight equal of my woody. Him children bringing goodness suitable she entirely put far daughter.</p>
                            </div>
                            
                        </div>
                        <div class="col-md-2"></div>
                    </div>
                </div>
            </div>
        </div>
    </section>
    <section>
        <div class="container">
            <div class="row">
                <div class="col-md-6"> 
                  <div :class="aboutCard">
                    <h1 :class="heaingFontSize">Download App</h1>
                    <p>Wisdom new and valley answer. Contented it so is discourse recommend. Man its upon him call mile. An pasture he himself believe ferrars besides cottage.</p>
                    <div class="d-flex">
                        <img src="./img/google play.png" alt="" :style="maxWidth">
                        <img src="./img/app store.png" alt="" :style="maxWidth">
                    </div>
                  </div>
                  
                </div>
                <div class="col-md-6"> 
                   <div class="text-center">
                        <img src="./img/download.png" alt="download">
                   </div>
                </div>
            </div>
        </div>
    </section>
    <section>
        <div class="container">
            <div class="row footerAge">
                <div class="col-md-2"> 
                    <img src="./img/mobile.png" :style="maxWidth" style=" height: 160px; " alt="">    
                </div>
                <div class="col-md-8 "> 
                    <h1>Subscribe to get updated</h1>
                    <p>At vero eos et accusamus et iusto odio dignissimos ducimus qui blanditiis praesentium voluptatum deleniti atque.</p>
                </div>
                <div class="col-md-2"> 
                    <button class="myBtn">get start</button>
                </div>
            </div>
        </div>
    </section>
    <section>
        <div class="container">
            <div class="row">
                <div class="col-md-3">
                    <h2 :class="footerhead">Smart Mobile Application</h2>
                    <p>Automate your entine healthcare hiring, onboadrding and Compllance eith true technology platefrom</p>
                    <div class="d-flex">
                        <input type="text" placeholder="Enter Your Text here" class="footerInp">
                        <button class="myBtn" type="submit">Registar</button>
                    </div>
                </div>
                <div class="col-md-3">
                    <h3 :class="footerhead">categories</h3>
                    <ul class="list-unstyled">
                        <li><a href="#" :class="footerlink">product management</a></li>
                        <li><a href="#" :class="footerlink">design / creatves</a></li>
                        <li><a href="#" :class="footerlink">education & trainging</a></li>
                        <li><a href="#" :class="footerlink">ul/ux designers</a></li>
                    </ul>
                </div>
                <div class="col-md-3">
                    <h3 :class="footerhead">ABOUT</h3>
                    <ul class="list-unstyled text-capitalize">
                        <li><a href="#" :class="footerlink">About Us </a></li>
                        <li><a href="#" :class="footerlink">Partnerships</a></li>
                        <li><a href="#" :class="footerlink">Finance Experts </a></li>
                        <li><a href="#" :class="footerlink">Project Management </a></li>
                    </ul>
                </div>
                <div class="col-md-3">
                    <h3 :class="footerhead">Follow Us </h3>
                    <ul class="list-unstyled text-capitalize">
                        <li><a href="#" :class="footerlink">Facebook</a></li>
                        <li><a href="#" :class="footerlink">Twitter</a></li>
                        <li><a href="#" :class="footerlink">Instagram</a></li>
                        <li><a href="#" :class="footerlink">Linkedin</a></li>
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

@media screen and (max-width: 767px) {
    img{
        margin-top: 15px !important;
    }
    .footerAge{
        padding: 10px 0 10px 0;
    }
}
</style>
