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
                <div class="d-flex main_div">
                    <div class="div_text_xp" id="div_trading_bot">
                        <div>
                            <h4 id="title_trading_bot">
                                Do you want me to work
                                <br> in your team ? 🤝📈
                            </h4>
                            <div id="trading_links">
                                <a href="https://github.com/IlyasFounas" target="_blank" class="mr-16">
                                    <img src="./../assets/github.png" class="logo" width="30px">
                                </a>
                                <a href="https://www.linkedin.com/in/ilyâs-founas-03a5b3257/" target="_blank">
                                    <img src="./../assets/in.png" class="logo">
                                </a>
                            </div>
                        </div>
                    </div>
                </div>

                <div class="mt-128">
                </div>
            </div>
        </div>

        <div class="div_global">
            <div class="text-white-50 para" id="about">
                <p>
                    Back in university, while studying <strong class="text-white">Computer Science at Valence in the
                        Drôme</strong>, I found myself drawn
                    <br>deeper into the world of <strong class="text-white">web development.</strong> What started as
                    small coding experiments quickly
                    <br>evolved into something more serious, and soon, I was fully immersed in building web
                    applications.
                </p>

                <p>
                    Joining <strong class="text-white">42 Lyon</strong> marked a turning point in my journey as a
                    developer. The unique, self-paced
                    <br>learning environment <strong class="text-white">pushed me out of my comfort zone</strong>, challenging me to solve problems
                    <br> independently while <strong class="text-white">collaborating</strong> with other <strong class="text-white">passionate programmers</strong>.
                    <br> It wasn’t just about learning to code but embracing a mindset of <strong class="text-white">innovation and adaptability</strong>.
                </p>


                <p>
                    When I’m not coding, you can find me <strong class="text-white">hiking</strong>, <strong
                        class="text-white">working out</strong> at the gym, or experimenting with new
                    <br><strong class="text-white">development ideas</strong>. I’m always on the lookout for new
                    challenges and technologies.
                </p>
            </div>
            <XP />
            <Project />
        </div>
    </div>
</template>

<style scoped>
#trading_links {
    margin-top: 20px;
}

#btn_trading_bot {
    background-color: black !important;
    margin-top: 15px;
    border-radius: 10px;
    padding: 10px;
    color: white;
}

#div_trading_bot {
    text-align: center;
    margin-top: 7rem;
    border-radius: 10px;
    padding: 10px;
    background-color: rgb(213, 234, 95) !important;
}

#title_trading_bot {
    color: rgb(0, 0, 0) !important;
    font-weight: bold;
}

.picture {
    border-radius: 10px;
    width: 25%;
}

.glob {
    padding-top: 6rem;
    padding-bottom: 6rem;
}

.logo {
    background-color: black;
    border-radius: 10px;
    ;
}

.logo:hover {
    scale: 1.3;
}

/* Réglages pour les écrans moyens */
@media screen and (max-width: 768px) {
    .picture {
        width: 50%;
    }
    #div_trading_bot {
        margin-top: 4rem;
        padding: 5px;
    }
    #title_trading_bot {
        font-size: 1.2rem;
    }
    .glob {
        padding-top: 3rem;
        padding-bottom: 3rem;
    }
    #btn_trading_bot {
        font-size: 0.9rem;
    }
}

/* Réglages pour les petits écrans */
@media screen and (max-width: 480px) {
    .picture {
        width: 70%;
    }
    .glob {
        padding-top: 2rem;
        padding-bottom: 2rem;
    }
    #title_trading_bot {
        font-size: 1rem;
    }
    #btn_trading_bot {
        font-size: 0.8rem;
        padding: 5px;
    }
    .logo {
        width: 20px;
        height: 20px;
    }
    #trading_links {
        margin-top: 10px;
    }
}
</style>