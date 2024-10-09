<script setup>
</script>

<template>
  <main class="mt-16 " id="experience">
    <div class="d-flex main_div">
      <div>
        <p class="date">
          OCTOBER - PRESENT
        </p>
      </div>
      <div>
        <p class="text-white title_xp">Actively seeking a Back-end Developer position</p>
        <p>
          I am looking for a job to gain as much experience as
          <br>possible in web development and teamwork. While waiting
          <br>to work with a team. I practice various modern technologies.
        </p>
      </div>
    </div>

    <div class="d-flex main_div">
      <div>
        <p class="date">
          SEPTEMBER - OCTOBER
        </p>
      </div>
      <div>
        <p class="text-white title_xp">Participant - 42 School Piscine</p>
        <p>
          <br>Immersed in a 26-day intensive environment, the 42 Piscine was 
          <br>a unique experience that pushed my limits in terms of focus 
          <br>and precision. I discovered my ability to work long hours with
          <br>unwavering concentration while tackling technical challenges.
          <br>This experience also gave me a true understanding of teamwork,
          <br>a fundamental aspect at 42. In addition to technical skills, 
          <br>the Piscine provided valuable learning both professionally and
          <br>socially, preparing me to collaborate in dynamic environments.
        </p>
      </div>
    </div>

    <div class="d-flex main_div">
      <div>
        <p class="date">
          2023 - 2024
        </p>
      </div>
      <div>
        <p class="text-white title_xp">Bachelor's Degree in Computer Science (Year 3) <br> And Apprenticeship at Acces Diffusion</p>
        <p>
          <br>During my third year of university, I had the opportunity
          <br>to explore various new technologies such as game programming,
          <br>Rust development, and mobile app development with Flutter. 
          <br>Concurrently, I worked as  full-stack developer at 
          <br>Accès Diffusion, where I contributed to building a 
          <br>ticket management system. This year was pivotal in both 
          <br>the completion of my bachelor's degree in computer science and 
          <br>in gaining valuable professional experience in the workplace.
        </p>
      </div>
    </div>

    <div class="d-flex main_div">
      <div>
        <p class="date">
          2022 - 2023
        </p>
      </div>
      <div>
        <p class="text-white title_xp">Bachelor's Degree in Computer Science (Year 2) <br> And Internship at Acces Diffusion</p>
        <p>
          <br>During my second year of university, I had the chance to apply 
          <br>and enhance my Back-end development skills through an internship
          <br>at Accès Diffusion. This experience allowed me to work on 
          <br>real-world projects, which was both enriching and enjoyable. 
          <br>It was a rewarding opportunity to put my theoretical knowledge
          <br>into practice and gain hands-on experience in a professional environment.
        </p>
      </div>
    </div>

    <div class="d-flex main_div">
      <div>
        <p class="date">
          2021 - 2022
        </p>
      </div>
      <div>
        <p class="text-white title_xp">Bachelor's Degree in Computer Science (Year 1)</p>
        <p>
          <br>In my first year, I gained a deep understanding of programming concepts and 
          <br>had the opportunity to experiment with various programming languages such as 
          <br>HTML, CSS, C, and MySQL. This foundational year was essential in building my 
          <br>technical skills and setting the stage for more advanced development 
          <br>work in the future.
        </p>
      </div>
    </div>
   </main>
</template>

<style scoped>
.title_xp
{
  font-size: 17px;
}
main
{
  padding-top: 5%;
  color: #a0a0a0;
}

.main_div {
  padding-top: 20px;
  padding-bottom: 20px;
  justify-content: space-evenly;
  transition: background-color 0.3s, border-color 0.3s, border-top 0.3s;
  z-index: 1;
  position: relative;
}

.main_div:hover
{
    background-color: #192439;/*#172035;*/
    border-radius: 20px;
    border-color: #3a435b !important;
    border-top: solid 0.5px;
}

.date
{
  font-size: 13px;
}

</style>