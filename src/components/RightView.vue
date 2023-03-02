<script setup>
import Card from "./Card.vue";
</script>
<template>
  <div>
    <div class="hidden md:flex gap-2 justify-end">
      <p
        class="bg-[#E7E7EB] p-[8px] flex justify-center rounded-full w-[40px] text-[18px] items-center text-center font-bold"
      >
        °C
      </p>
      <p
        class="bg-[#585676] p-[8px] flex justify-center rounded-full w-[40px] text-[18px] items-center text-center text-white font-bold"
      >
        °F
      </p>
    </div>

    <!-- cards displaying the temp per days of the week -->
    <div class="grid grid-cols-2 md:grid-cols-5 gap-7 mt-[66px]">
      <Card
        title="Tomorrow"
        icon="https://www.cvale.com.br/site/web-files/imagens/icones-clima/IsoRainSwrsDay.png"
        temp="16°C"
        tempMin="11°C"
      />
      <Card
        title="Sun. 7 Jun"
        icon="https://www.cvale.com.br/site/web-files/imagens/icones-clima/IsoRainSwrsDay.png"
        temp="16°C"
        tempMin="11°C"
      />
      <Card
        title="Mon. 8 Jun"
        icon="https://www.cvale.com.br/site/web-files/imagens/icones-clima/IsoRainSwrsDay.png"
        temp="16°C"
        tempMin="11°C"
      />
      <Card
        title="Tue. 9 Jun"
        icon="https://www.cvale.com.br/site/web-files/imagens/icones-clima/IsoRainSwrsDay.png"
        temp="16°C"
        tempMin="11°C"
      />
      <Card
        title="Wed. 10 Jun"
        icon="https://www.cvale.com.br/site/web-files/imagens/icones-clima/IsoRainSwrsDay.png"
        temp="16°C"
        tempMin="11°C"
      />
    </div>
  </div>
</template>
