<script setup>
defineProps({
  // props go here
  title: {
    type: String,
    default: "Tomorrow",
  },
  icon: {
    type: String,
    default:
      "https://www.cvale.com.br/site/web-files/imagens/icones-clima/IsoRainSwrsDay.png",
  },
  temp: {
    type: String,
    default: "16°C",
  },
  tempMin: {
    type: String,
    default: "11°C",
  },
});
</script>

<template>
  <div>
    <div
      class="flex flex-col gap-4 items-center justify-center px-[20px] md:px-[24px] py-[20px] bg-[#1E213A]"
    >
      <h2 class="text-white">{{ title }}</h2>
      <img
        :src="icon"
        alt=""
        class="h-[62px] w-[54px] overflow-hidden object-cover"
      />
      <div class="flex gap-4">
        <p class="text-white">{{ temp }}</p>
        <p class="text-gray-400">{{ tempMin }}</p>
      </div>
    </div>
  </div>
</template>
