<script setup>
import navbar from './components/navbar.vue';
import home from './components/home.vue';
import skills from './components/skills.vue';
import projects from './components/projects.vue';
import contact from './components/contact.vue';
import footers from './components/footer.vue';
</script>

<template>
  <div class="appContainer" id="home">
  <navbar/>
  <div class="parent" >
  <home />
  <div class="line" id="skills"></div>
  <skills />
  <div class="line" id="projects"></div>
  <projects/>
  <div class="line" id="contact"></div>
  <contact/>
  <div class="line" id="footer"></div>
  <footers/>
  </div>
  </div>
</template>

<style>
#app {
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  top:0;
  margin:0 auto;
  display: flex;
  flex-direction: column;
  align-items: center;
  min-height: 100vh;
  width: 100%;
  height: 100%;
}
.line{
  width: 100%;
  height: 30px;
  margin-top: 50px;
  margin-bottom: 30px;
  border-top: #C8ACD6 1px dashed;
}
#footer{
  margin-top: 40px;
  margin-bottom: 0px;
  height: 0px;
}
#skills{
  margin-bottom: 50px;
}
.parent {
  max-width: 675px;
  margin-top: 100px;
  top:0;
  padding:0;
  margin-left: 20px;
  margin-right: 20px;
}

.appContainer{
  width: 100%;
  display: flex;
  flex-direction: column;
  align-items: center;
  min-height: 100vh;
}
@media screen and (max-width:600px){
  
 }
</style>
