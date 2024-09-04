<template>
    <div class="contactContainer">
        <h1>Contact</h1>
        <p class="headers">Reach out to me</p>
        <p class="description">I'm open to connecting. Feel free to reach out via email or on my <a href="https://www.linkedin.com/in/varun-s-054771298/" target="_blank">LinkedIn</a> profile.</p>
        <a href="mailto:varunsomashekar18@gmail.com" target="_blank" class="mail">varunsomashekar18@gmail.com</a>
    </div>
</template>
<style>
.contactContainer{
    width:100%;
    height: 200px;
    display: flex;
    flex-direction: column;
    align-items: center;
}
.contactContainer h1{
  font-size: 1.3rem;
  font-weight: 600;
  color: #D6BD98;
}
.headers{
  color: #C8ACD6;
  font-size: 1.1rem;
  margin:0 5px;
}
.description{
    font-size: 1rem;
    color:#F4EAE0;
}
.mail{
    font-size: 1.2rem;
    color:#3b689e;
    font-weight: 600;
}
.description a{
    text-decoration: none;
    color:#3b689e;
}

</style>