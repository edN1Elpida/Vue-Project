<template>
  <div class="profile">
    <h1>Pendidikan</h1>
    <hr>
<h2>2020-2023 <br>
  SMKS Taruna Bhakti <br>
  Rekayasa Perangkat Lunak</h2>

  
    <h1>Pengalaman</h1>
    <hr class="p2">
    <h1 class="p">SMKS Taruna Bhakti 2021</h1>
<h2>-Team Project Food Delivery (Figma & Web (CSS & Java Script)) <br>
-Website Sarpras <br>
-Implementation Figma to Bootstrap <br>
-Simple Landing Page Bootstrap <br>
-Mockup Aplikasi Music-In Aja</h2>
<hr class="p3">
<h1 class="p">SMKS Taruna Bhakti 2022</h1>
<h2>-Website Crud Agenda Guru (Laravel) <br>
-Team Project Website Peduli Diri (Laravel)</h2>

<h1>Bahasa</h1>
    <hr>
    <div class="flex">
      <h3>Indonesia</h3>
        <h3>100%</h3>
      <div class="bahasa_bar">
        <span class="bahasa_percetage bahasa_indonesia"></span>
      </div>
      <h3>English</h3>
        <h3>70%</h3>
      <div class="bahasa_bar">
        <span class="bahasa_percetage bahasa_english"></span>
      </div>
        <h3>Japanese</h3>
        <h3>40%</h3>
      <div class="bahasa_bar">
        <span class="bahasa_percetage bahasa_japanese"></span>
      </div>
  </div>
  </div>
</template>

<style>

hr{
  width: 9rem;
}

.p2{
  width: 9.5rem;
}
.p3{
  width: 15rem;
}


.profile h1{
  font-size: 1.7rem;
  font-weight: 500;
  margin-bottom: 0.4rem;
  color: var(--color-heading);
}
.profile .p{
  font-size: 1.3rem;
  font-weight: 300;
  margin-bottom: 0.4rem;
  color: var(--color-heading);
}
.profile h2{
  font-size: 1rem;
  font-weight: 200;
  margin-bottom: 0.4rem;
  color: var(--color-heading);
}


.bahasa_bar, .bahasa_percetage{
  margin-top: 5px;
  height: 5px;
  border-radius: 25rem;
}

.bahasa_bar{
  background-color: black;
}

.bahasa_percetage{
  display: block;
  background-color: hsla(160, 100%, 37%, 1);
}

.bahasa_indonesia{
  width: 100%;
}

.bahasa_english{
  width: 70%;
}

.bahasa_japanese{
  width: 40%;
}

@media (min-width: 1024px) {
  .profile{
    display: flex;
    flex-direction: column;
  }
}
</style>
