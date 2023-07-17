<script setup>
const navbar = 'navbar navbar-expand-lg navbar-light'
const navitem = 'nav-item'
const navlink = 'nav-link'
const application = 'smart application'
const marginSmart = 'margin : 12px 0 0 0'

const container = 'container'
const row = 'row'
const colmd4 = 'col-md-4'
const capitalize = 'text-capitalize'
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
                    <h3 :class="capitalize" :style="marginSmart">{{application}}</h3>
                </div>
                <div :class="colmd4" :style="marginSmart">
                    <button class="myBtn" >login</button>
                    <button class="myBtn">sign up</button>
                </div>
            </div>
        </div>
    </section>
</template>

<style scoped></style>