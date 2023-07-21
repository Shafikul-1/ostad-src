<script setup>
 import menu from './menu.vue'
 import hero from './hero.vue'
 import companylogo from './companylogo.vue'
 import usercart from './usecart.vue'
 import undevtchart from './investchart.vue'
 import ceo from './ceo.vue';
 import pricing from './pricing.vue'
 import faq from './faq.vue'
 import faqsec from './faqsec.vue'
 import trial from './trial.vue';
 import footar from './footar.vue'

</script>

<template>

<menu/>
<hero/>
<companylogo/>
<usercart/>
<undevtchart/>
<ceo/>
<pricing/>
<div class="flex">
    <faq class="w-1/2"/>
    <faqsec class="w-1/2"/>
</div>
<trial/>
<footar/>

</template>

<style scoped></style>
