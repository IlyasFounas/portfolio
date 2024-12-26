<script setup>
import XP from './Crypto.vue'
import Project from './Projects.vue'

</script>

<template>
    <div class="d-flex justify-content-center glob"> <!--align-items-center-->
        <div id="parent_fixed">
            <div id="div_fixed">
                <p><img src="./../assets/ifounas.jpg" class="picture"></p>
                <p class="text-white title"><strong>Ilyâs Founas</strong></p>
                <p class="text-white title_bis">
                    Student at 42 - Lyon France</p>
                <p class="text-white-50">
                    I build applications with passion and precision, 
                    <br>thriving in projects where creativity meets innovation!
                </p>
                <div class="text-white mt-16">  
                    <div class="section-title">
                        <span class="line"></span>
                        <span class="title ul"><a href="#" id="link-about">ABOUT</a></span>
                    </div>
                    <div class="section-title">
                        <span class="line"></span>
                        <span class="title ul"><a href="#experience" id="link-experience">EXPERIENCE</a></span>
                    </div>
                    <div class="section-title">
                        <span class="line"></span>
                        <span class="title ul"><a href="#projects" id="link-projects">PROJECTS</a></span>
                    </div>
                </div>

                <div class="mt-128">
                    <a href="https://github.com/IlyasFounas" target="_blank" class="mr-16">
                        <img src="./../assets/github.png" class="logo" width="30px">
                    </a>
                    <a href="https://www.linkedin.com/in/ilyâs-founas-03a5b3257/"  target="_blank" class="mr-16">
                        <img src="./../assets/in.png" class="logo">
                    </a>
                    <!--<a href="https://www.instagram.com/ilyasfns/" target="_blank">
                        <img src="./../assets/insta.png" class="logo">
                    </a>-->
                </div>
            </div>
        </div>

        <div class="div_global">
            <div class="text-white-50 para" id="about">
                <p>
                    Back in university, while studying <strong class="text-white">Computer Science at Valence in the Drôme</strong>, I found myself drawn 
                    <br>deeper into the world of <strong class="text-white">web development.</strong> What started as small coding experiments quickly
                    <br>evolved into something more serious, and soon, I was fully immersed in building web applications.
                </p>

                <p>
                    Since then, I've had the opportunity to work as a full-stack web developer, both during a three-
                    <br>month internship and a <strong class="text-white">year-long apprenticeship</strong>. These experiences allowed me to sharpen my skills
                    <br>and gain hands-on experience in building robust, dynamic applications.
                </p>

                <p>
                    These days, I spend most of my time working on personal projects, including a <strong class="text-white">3D game</strong> and a 
                    <br> <strong class="text-white">culinary creation website</strong> built with <strong class="text-white">Symfony</strong>. I particularly enjoy the challenge of developing
                    <br>applications that are both functional and visually appealing, combining design and code into 
                    <br>seamless experiences.
                </p>

                <p>
                    When I’m not coding, you can find me <strong class="text-white">hiking</strong>, <strong class="text-white">working out</strong> at the gym, or experimenting with new 
                    <br><strong class="text-white">development ideas</strong>. I’m always on the lookout for new challenges and technologies, whether it’s
                    <br>improving my skills in <strong class="text-white">Vue.js</strong> or diving into game development with <strong class="text-white">Godot</strong>.
                </p>
            </div>
            <XP />
            <Project />
        </div>
    </div>
</template>

<style scoped>
.picture 
{
    width: 25%;
}
.glob
{
    padding-top: 6rem;
    padding-bottom: 6rem;
}

.logo:hover
{
    scale: 1.2;
}

</style>