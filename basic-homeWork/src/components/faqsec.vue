<script setup>
import { ref, reactive } from 'vue'
const activeIn = reactive([true])

import faqData from '../data/faq'
</script>
<template>
    <section>
        <div class="faq">
            <div v-for="(faq, index) in faqData" class="border bg-slate-300 pl-5 mt-4 hover:bg-slate-400 rounded-md" :class="activeIn[index] ? 'bg-slate-400' : ''" :key="index">
               <div  @click="activeIn[index] = !activeIn[index]" class="faq_h  text-1xl font-bold cursor-pointer py-4  flex">
                    <i class="fa-solid pt-1 font-bold mr-2" :class="activeIn[index] ? 'fa-xmark text-white' : 'fa-plus'"></i>
                    <h3 :class="activeIn[index] ? 'text-white' : ''">{{ faq.head }}</h3>
               </div> 
                <div v-show="activeIn[index]" class="faq_p pb-6">
                    <p>{{ faq.body }}</p>
                </div>
            </div>
        </div>
    </section>
</template>
<style scoped></style>