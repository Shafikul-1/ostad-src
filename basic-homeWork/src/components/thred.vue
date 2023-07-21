<!-- Extra Work test -->
<!-- <div class="thredfaq text-center ">
    <img src="https://media.istockphoto.com/id/1426039616/photo/text-faq-on-wooden-blocks-with-letters-on-a-white-background-reflection-of-the-caption-on-the.jpg?b=1&s=170667a&w=0&k=20&c=-ZGWMZUtdkpConZiA2I2T_cewkb4AgHPuwBNoa-32-E=" alt="">
    <h1 class=" text-4xl uppercase font-bold my-5">faq</h1>
    <thred/>
</div> -->

<script setup>
    import { ref,reactive} from 'vue'
    const showing = reactive([false])
    import faqjs from '../data/faq'
    console.log(faqjs)
</script>
<template>
    <div class="bg-gray-200 my-5 border-4 border-green-500" v-for="(faq, index) in faqjs" :key="index">
        <div class="faqHead flex" @click="showing[index] = !showing[index]">
            <i class="fa-solid" :class="!showing[index] ? 'fa-plus' : 'fa-xmark'"></i>
            <h2 class="font-bold text-xl hover:text-indigo-800  cursor-pointer">{{ faq.head }}</h2>
        </div>
        <div class="faqP" v-show="showing[index]">
            <p>{{ faq.body }}</p>
            <a class=" bg-indigo-300 rounded" href="#" :href="faq.link">click here</a>
        </div>
    </div>
</template>
<style scoped></style> 


