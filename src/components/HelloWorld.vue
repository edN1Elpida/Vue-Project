<script setup>
defineProps({
  msg: {
    type: String,
    required: true
  },
  msg1: {
    type: String,
    required: true
  }
})


import TeleponIcon from './icons/IconTelepon.vue'
import EmailIcon from './icons/IconEmail.vue'
import GithubIcon from './icons/IconGithub.vue'
import LinkedinIcon from './icons/IconLinkedin.vue'
</script>

<template>
  <div class="greetings">
    <div class="flex">
      <h1 class="green">{{ msg }}</h1>
      <h2 class="kelas">{{ msg1 }}</h2>
    </div>
    <hr>
    <h3>
      Saya adalah seorang Web Developer pemula dengan keahlian dasar. <br>
      Untuk saat ini saya sedang mempelajari Laravel dan Backend. <br>
      Saya juga berpengalaman dalam berbicara di depan publik. <br>
      Keahlian lain saya suka menganalisis masalah dan merumuskan solusi bersama dengan tim saya. <br>
      Saya juga tertarik untuk mempeajari hal-hal yang baru. <br>
    </h3>
    <hr>
    <ul>
      <li>
        <h3><TeleponIcon />   <span>0888-6339-296</span></h3>
      </li>
      <li>
        <h3><EmailIcon />   <span>elpidaedn@gmail.com</span></h3>
      </li>
      <li>
        <h3><GithubIcon />   <span>github.com/edN1Elpida</span></h3>
      </li>
      <li>
        <h3><LinkedinIcon />   <span>www.linkedin.com/in/rohmadani-dwi-oktaviansyah</span></h3>
      </li>
    </ul>
  </div>
</template>

<style scoped>

ul{
  list-style: none;
}

ul li h3{
  margin-left: -2.5rem;
}

hr{
  width: 29rem;
}

h1 {
  color: #71c3f7;
  font-weight: 500;
  font-size: 1.5rem;
  top: -10px;
}

h2 {
  color: #71c3f7;
  font-weight: 300;
  font-size: 0.7rem;
  top: -3px;
  margin: auto;
}

h3 {
  margin-bottom: 0.7rem;
  margin-top: 0.7rem;
  color: #f6f6f6;
  font-size: 1rem;
}

.flex{
  display: flex;
}

/* .greetings {
  background-color: ;
} */

.greetings h1,
.greetings h3 {
  text-align: center;
}

@media (min-width: 1024px) {
  .greetings h1,
  .greetings h3 {
    text-align: left;
  }
}
</style>
