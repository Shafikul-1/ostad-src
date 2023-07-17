<script setup>
const container = 'container'
const row = 'row'
const colmd2 = 'col-md-2'
const colmd6 = 'col-md-6'
const capitalize = 'text-capitalize'
const client = 'our clients'
const clientP = 'Wisdom new and valley answer. Contented it so is discourse recommend. Man its upon him call mile. An pasture he himself believe ferrars besides cottage.'
const top5 = 'mt-5'
const heaingFontSize =  'fs-1 fw-bold'
const clinetimg = 'background: white; margin: 0 32px 0 0; box-shadow: 0 2px 1px 0 gray; border-radius: 6px; padding: 23px; mt-3'
</script>

<template>
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
                            <img src="../img/client.png" alt=""  :style="clinetimg">
                            <img src="../img/client1.png" alt=""  :style="clinetimg">
                        </div>
                        <div :class="colmd6">
                            <img src="../img/client2.png" alt=""  :style="clinetimg">
                            <img src="../img/client3.png" alt=""  :style="clinetimg">
                        </div>
                    </div>
                    <div class="row mt-4 mb-5">
                        <div :class="colmd6">
                          <img src="../img/client4.png" alt=""  :style="clinetimg">
                          <img src="../img/client5.png" alt=""  :style="clinetimg">
                        </div>
                        <div :class="colmd6">
                          <img src="../img/client6.png" alt=""  :style="clinetimg">
                          <img src="../img/client7.png" alt=""  :style="clinetimg">
                        </div>
                    </div>
                </div>
                <div class="col-md-1"></div>
            </div>
        </div>
    </section>
</template>

<style scoped>

</style>
