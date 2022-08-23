<script setup>
import Skills from '@/components/TheSkill.vue'
</script>

<template>
  <main>
    <div class="welcome">
    <Skills />
    
    </div>
  <div class="next">
    <a href="">Next></a>
  </div>
  </main>
</template>


<style scoped>
.next{
  width: 45px;
  height: 30px;
  display: flex;
}

.next a{
  box-shadow: 1px;
  margin-left: 37rem;
}
</style>