<script setup>
function scrollTo(refName){
    const element=document.getElementById(refName);
    element.scrollIntoView({behavior: "smooth", block: "start"});
}
</script>
<template>
        <div class="container">
            <div class="navmenu">
                <li><a @click="scrollTo('home')">home</a></li>
                <li><a @click="scrollTo('skills')">skills</a></li>
                <li><a @click="scrollTo('projects')">projects</a></li>
                <li><a @click="scrollTo('contact')">contact</a></li>
                <li><a href="https://drive.google.com/file/d/1tgRsj-4rD_H2KWkO2277-iD1VW-pT3M3/view?usp=sharing" target="_blank">resume</a></li>
            </div>
        </div>
</template>


<style>


.navmenu{
    list-style: none;
    display: flex;
    flex-direction: row;
    align-items: center;
    justify-content: center;
    margin:0;
    width: 100%;
    height: 100%;
    color: #ad84c1 ;
    background: rgba(0, 0, 0, 0.1);
    border-radius: 30px;
    box-shadow: 0 4px 30px rgba(6, 21, 34, 0.3);
    backdrop-filter: blur(10px);
    -webkit-backdrop-filter: blur(10px);
    border: 1px solid rgba(255, 255, 255, 0.226);
}
.navmenu li{
    margin:0 10px;
    display: flex;
    flex-direction: row;
    align-items: center;
    justify-content: center;
    height: 22px;
}
.container{
    position: fixed !important;
    display: flex;
    flex-direction: row;
    align-items: center;
    justify-content: center;
    top:0;
    margin-top: 10px;
    height: 60px;
    font-size: 1rem;
    font-weight: 500;
    width:400px;
}
.navmenu li:hover{
    background-color: #ad84c1 ;
    color: #021526;
    border-radius: 3px;
    cursor: pointer;
}
li a{
    text-decoration: none;
    color: #ad84c1 ;
}
li a:hover{
    color: #021526;
}
</style>
