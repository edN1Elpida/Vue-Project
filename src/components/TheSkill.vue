<script setup>
import SkillItem from './SkillItem.vue'
import HTMLIcon from './icons/IconHTTML.vue'
import CSSIcon from './icons/IconCSS.vue'
import BIcon from './icons/IconB.vue'
import FigmaIcon from './icons/IconFigma.vue'
import LaravelIcon from './icons/IconLaravel.vue'
import JSIcon from './icons/IconJS.vue'
</script>

<template>
  <SkillItem>
    <template #icon>
      <HTMLIcon />
    </template>
    <template #heading>HTML</template>
      <div class="flex">
        <h3>90%</h3>
      </div>
      <div class="skills_bar">
        <span class="skills_percetage skills_html"></span>
      </div>
  </SkillItem>

  <SkillItem>
    <template #icon>
      <CSSIcon />
    </template>
    <template #heading>CSS</template>
      <div class="flex">
        <h3>90%</h3>
      </div>
      <div class="skills_bar">
        <span class="skills_percetage skills_css"></span>
      </div>
  </SkillItem>

  <SkillItem>
    <template #icon>
      <BIcon />
    </template>
    <template #heading>Bootstrap</template>
      <div class="flex">
        <h3>85%</h3>
      </div>
      <div class="skills_bar">
        <span class="skills_percetage skills_b"></span>
      </div>
  </SkillItem>

  <SkillItem>
    <template #icon>
      <FigmaIcon />
    </template>
    <template #heading>Figma</template>
      <div class="flex">
        <h3>85%</h3>
      </div>
      <div class="skills_bar">
        <span class="skills_percetage skills_figma"></span>
      </div>
  </SkillItem>

  <SkillItem>
    <template #icon>
      <LaravelIcon />
    </template>
    <template #heading>Laravel</template>
      <div class="flex">
        <h3>75%</h3>
      </div>
      <div class="skills_bar">
        <span class="skills_percetage skills_laravel"></span>
      </div>
  </SkillItem>

  <SkillItem>
    <template #icon>
      <JSIcon />
    </template>
    <template #heading>Java Script</template>
      <div class="flex">
        <h3>30%</h3>
      </div>
      <div class="skills_bar">
        <span class="skills_percetage skills_js"></span>
      </div>
  </SkillItem>
</template>

<style scoped>

.skills_bar, .skills_percetage{
  margin-top: 5px;
  height: 5px;
  border-radius: 25rem;
}

.skills_bar{
  background-color: black;
}

.skills_percetage{
  display: block;
  background-color: hsla(160, 100%, 37%, 1);
}

.skills_figma, .skills_b{
  width: 85%;
}

.skills_html, .skills_css{
  width: 90%;
}

.skills_laravel{
  width: 75%;
}

.skills_js{
  width: 30%;
}

</style>