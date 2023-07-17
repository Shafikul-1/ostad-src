<script setup>
const subscribe = 'Subscribe to get updated'
const subscribeP = 'At vero eos et accusamus et iusto odio dignissimos ducimus qui blanditiis praesentium voluptatum deleniti atque.'
const colmd2 = 'col-md-2'
const maxWidth = 'max-width: 100%'
const container = 'container'
</script>
<template>
    <section>
        <div :class="container">
            <div class="row footerAge">
                <div :class="colmd2"> 
                    <img src="../img/mobile.png" :style="maxWidth" style=" height: 160px; " alt="">    
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
</template>
<style scoped></style>