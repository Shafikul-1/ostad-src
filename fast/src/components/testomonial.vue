<script setup>
const container = 'container'
const row = 'row'
const colmd12 = 'col-md-12'
const colmd2 = 'col-md-2'
const Testimonials = 'Testimonials'
const testomonialP = 'Wisdom new and valley answer. Contented it so is discourse recommend. Man its upon him call mile. An pasture he himself believe ferrars besides cottage.'

</script>

<template>
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
</template>
<style scoped></style>