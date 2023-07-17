<script setup>
const container = 'container'
const row = 'row'
const colmd6 = 'col-md-6'
const capitalize = 'text-capitalize'
const testomonialManInfo = 'Product designer - Besnik'
const manicon = 'https://cdn-icons-png.flaticon.com/512/4128/4128176.png'
const man = ' margin: 11px 0px -14px 20px;'
const testomonialicon = 'width: 40px; height:40px; margin: 18px 0'
const testomonialP2 = 'our company, we do ongoing research with our target audience. This includes 30-45 minute phone interviews. It was difficult to conduct the interview, really listen, and ask good follow up questions'


const testomnialManName = 'Custom IT Solutions Firm'
</script>
<template>
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
</template>
