<script setup>
const container = 'container'
const row = 'row'
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
const footerlink = 'text-decoration-none text-capitalize text-black'
const footerhead = 'fs-4 font-bold mt-5 text-uppercase'

const footerHead = 'Smart Mobile Application'
const footerP = 'Automate your entine healthcare hiring, onboadrding and Compllance eith true technology platefrom'

</script>
<template>
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
</template>
<style scoped></style>