<script setup>
import Logo from '/images/LogoWhite.svg'
import MapIcon from '/images/icon-location.svg'
import PhoneIcon from '/images/icon-phone.svg'
import MailIcon from '/images/icon-email.svg'
import Social from './Social.vue'
</script>

<template>

    <footer class="bg-[#00252e] text-white px-6 lg:px-20 pt-20 lg:pt-28 pb-4">
        <img class="w-48 mb-4" :src="Logo" alt="Logo Huddle"/>
        
        <div class="lg:grid lg:grid-cols-3 lg:items-start lg:gap-x-12 lg:pb-8">

            <div>
                <div class="flex items-start gap-x-3 mb-4">
                    <img class="mt-1.5" :src="MapIcon" alt="" />
                    <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor 
                        incididunt ut labore et dolore magna aliqua
                    </p>
                </div>
                <div class="flex items-center gap-x-3 mb-4">
                    <img class="" :src="PhoneIcon" alt="" />
                    <p>+1-543-123-4567</p>
                </div>
                <div class="flex items-center gap-x-3">
                    <img class="" :src="MailIcon" alt="" />
                    <p>example@huddle.com</p>
                </div>
            </div>

            <nav aria-label="Navigation Footer" class="my-10 lg:my-0">
                <ul class="lg:flex lg:justify-around">
                    <div class="space-y-3 lg:sapce-y-0 mb-3">
                        <li><a href="#" class="hover:underline">About Us</a></li>
                        <li><a href="#" class="hover:underline">What We Do</a></li>
                        <li><a href="#" class="hover:underline">FAQ</a></li>
                    </div>
                    <div class="space-y-3 lg:sapce-y-0">
                        <li><a href="#" class="hover:underline">Career</a></li>
                        <li><a href="#" class="hover:underline">Blog</a></li>
                        <li><a href="#" class="hover:underline">Contact Us</a></li>
                    </div>
                </ul>
            </nav>

            <div class="lg:flex lg:flex-col h-full justify-between">
                <Social />
                <p class="text-xs text-center lg:text-left">&copy; Copyright 2018 Huddle. All rights reserved.</p>
            </div>
        
        </div>
        
        <p class="text-xs text-center mt-4 text-[#808d99]">
            Challenge by <a class="font-bold hover:text-white" href="https://www.frontendmentor.io?ref=challenge" target="_blank">Frontend Mentor</a>. 
            Coded by <a class="font-bold hover:text-white" href="https://github.com/VickyAzola/LandingPage-Vue.js" target="_blank">Victoria Azola</a>.
        </p>
    </footer>
    
</template>

