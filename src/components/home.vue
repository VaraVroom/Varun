<template>
    <div
      class="homeContainer"
      data-aos="fade"
      data-aos-once="true"
      data-aos-duration="1000"
>
      <div class="greet"><p class="hello">hello there!</p>
      <div class="description">
    <p>I am Varun S from Bengaluru, Karnataka, a B.Tech final year student pursuing Computer Science with a strong passion for web development.<br><br>
        I'm a detail-oriented individual who keeps goals and tasks well-organized to stay productive. The skills I've honed in a dynamic and competitive university environment define who I am, and I'm eager to apply and refine them in any opportunity that comes my way.</p>
      </div>
      <div class="socials">
        <a href="https://www.linkedin.com/in/varun-s-054771298/" target="_blank">
          <img src="../assets/linkedin.svg">
        </a>
        <a href="https://www.github.com/VaraVroom" target="_blank">
          <img src="../assets/github.svg">
        </a>
        <a href="mailto:varunsomashekar18@gmail.com" target="_blank">
          <img src="../assets/mail.svg">
        </a>
      </div>
      </div>
    </div>
</template>

<style>
.greet{
    color: black;
}
.hello{
  font-size: 1.3rem;
  font-weight: 600;
  color: #D6BD98;
}
.socials img{
  height:20px;
  width:20px;
}
.socials a{
  height:30px;
  width:30px;
  display: flex;
  flex-direction: row;
  justify-content: center;
  align-items: center;
  border-radius: 3px;
  margin-right: 5px;
  background-color: rgba(138, 137, 137, 0.568);
}
.socials{
  display: flex;
  flex-direction: row;
  align-items: center;
  margin-top:20px;
}
.socials a:hover{
  background-color: #7e97bb9c;
}
.description{
  font-size: 1rem;
  font-weight: 500;
  color:#F4EAE0;
}
</style>