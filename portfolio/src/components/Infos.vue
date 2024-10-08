<script setup>
import Crypto from './Crypto.vue'
</script>

<template>
    <div class="d-flex justify-content-center"> <!--align-items-center-->

        <div>
            <p class="text-white title"><strong>Ilyâs Founas</strong></p>
            <p class="text-white title_bis">Junior Backend Developer</p>
            <p class="text-white-50">
                I build applications with passion and precision !
            </p>
            <div class="text-white mt-16">
                <div class="section-title">
                    <span class="line"></span>
                    <span class="title ul"><a href="#about">ABOUT</a></span>
                </div>
                <div class="section-title">
                    <span class="line"></span>
                    <span class="title ul"><a href="#experience">EXPERIENCE</a></span>
                </div>
                <div class="section-title">
                    <span class="line"></span>
                    <span class="title ul"><a href="#">PROJECTS</a></span>
                </div>
            </div>
        </div>
        <div id="about">
            <div class="text-white-50 para">
                <p>
                    Back in university, while studying <strong class="text-white">Computer Science at Valence in the Drôme</strong>, I found myself drawn 
                    <br>deeper into the world of web development. What started as small coding experiments quickly
                    <br>evolved into something more serious, and soon, I was fully immersed in building web applications.
                </p>

                <p>
                    Since then, I've had the opportunity to work as a full-stack web developer, both during a three-
                    <br>month internship and a <strong class="text-white">year-long apprenticeship</strong>. These experiences allowed me to sharpen my skills
                    <br>and gain hands-on experience in building robust, dynamic applications.
                </p>

                <p>
                    These days, I spend most of my time working on personal projects, including a <strong class="text-white">3D game</strong> and a 
                    <br>culinary creation website built with Symfony.I particularly enjoy the challenge of developing
                    <br>applications that are both functional and visually appealing, combining design and code into 
                    <br>seamless experiences.
                </p>

                <p>
                    When I’m not coding, you can find me <strong class="text-white">hiking</strong>, <strong class="text-white">working out</strong> at the gym, or experimenting with new 
                    <br>development ideas. I’m always on the lookout for new challenges and technologies, whether it’s
                    <br>improving my skills in <strong class="text-white">Vue.js</strong> or diving into game development with <strong class="text-white">Godot</strong>.
                </p>
            </div>
            <Crypto />
        </div>
    </div>
</template>