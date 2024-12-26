<script setup>
</script>

<template>
  <main class="mt-16 para" id="projects">
    <div class="d-flex main_div">
      <div class="div_date">
        <p class="date"><img src="./../assets/AD.PNG" id="AccesDiffusion"></p>
      </div>
      <div class="div_text_xp">
        <p class="text-white title_xp">AD gestion tickets</p>
        <p>
          AD Gestion Tickets is a professional project I worked on during my 
          <br>apprenticeship at Accès Diffusion. My role focused on development
          <br>and testing, though the project, requiring 1.5 years of work, 
          <br>was not fully completed during my time there. The site is designed to
          <br>allow Accès Diffusion's clients to create tickets for products and software
          <br>distributed by the company. This experience was invaluable, improving my 
          <br>technical and communication skills within a professional IT team.  
        </p>
      </div>
    </div>
    <div class="d-flex main_div">
      <div class="div_date">
        <p class="date"><img src="./../assets/symrecipe.PNG" id="symrecipe"></p>
      </div>
      <div class="div_text_xp">
        <p class="text-white title_xp">Symrecipe</p>
        <p>
          Symrecipe is a project built with the Symfony framework, designed 
          <br>for sharing culinary recipes. This small project allowed me 
          <br>to explore and master some of Symfony's most essential features.  
          <br>It was a rewarding experience that strengthened my web development skills!  
        </p>
      </div>
    </div>
    <div class="d-flex main_div">
      <div class="div_date">
        <p class="date"><img src="./../assets/flutter_app.PNG" id="chat"></p>
      </div>
      <div class="div_text_xp">
        <p class="text-white title_xp">Flutter Chat App</p>
          <p>
            During my final year of IT studies, I worked on a group project where I developed the chat system  
            <br>of our application using Flutter and Google Firebase. This experience allowed me to dive deep into  
            <br>the Flutter ecosystem and use Google Firebase to manage the database.  
            <br>It was an incredible opportunity to learn and apply new technologies in a practical setting!  
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
  margin-top: 20px;
  padding-top: 20px;
  padding-bottom: 20px;
  transition: background-color 0.3s, border-color 0.3s, border-top 0.3s;
  border-radius: 20px;
  z-index: 1;
  position: relative;
}

.main_div:hover
{
    background-color: #192439;/*#172035;*/
    
    border-color: #3a435b !important;
    border-top: solid 0.5px;
}

.date
{
  margin-left: 10px;
  margin-right: 40px;
  font-size: 13px;
}

.div_date
{
  position: absolute;
}

.div_text_xp
{
  margin-left: 190px;
}

#chat
{
  margin-left: 10%;
  width: 22%;
  border-radius: 10%;
}


#symrecipe
{
  width: 20%;
  height: 30%;
  border-radius: 10%;
}
#AccesDiffusion
{
  width: 20%;
  height: 30%;
  border-radius: 10%;
}

#accesdiffusion
{
  width: 30%;
  border-radius: 10%;
}

</style>