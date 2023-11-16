<script setup>
  import HomeviewOne from '../components/Homeviews/HomeviewOne.vue';
  import HomeviewOnes from '../components/Homeviews/HomeviewOnes.vue';
  import SpecEffect from '../components/Homeviews/SpecEffect.vue';
  import HomeviewTwo from '../components/HomeviewTwo/HoemviewTwo.vue'
</script>

<template>
  <section class="relative">  
    <div class="container mx-auto">
      <HomeviewOne/>
      <SpecEffect/>
      <p class="text-[21px] text-center text-white font-[500] mt-[120px] md:mt-[176px] lg:mt-[260px] font-sans">Biz bilan o'sayotgan kompaniyalar</p>
      <HomeviewOnes class=""/>
      <HomeviewTwo/>
    </div>
  </section>
</template>
