<template>
  <div class="font-Raleway">
    <div class="flex flex-row justify-between items-center mb-[30px]">
      <input
        type="text"
        placeholder="Search for places"
        class="px-[11px] py-[14px] border-none text-center bg-gray-600 text-white-800 font-medium placeholder:text-white rounded-md text-[16px]"
      />
      <div
        class="bg-gray-600 px-2 py-2 rounded-full flex items-center justify-center cursor-pointer"
      >
        <font-awesome-icon
          icon="fa-regular fa-compass"
          class="text-white h-5 w-5"
        />
      </div>
    </div>

    <!-- middle -->
    <div class="flex flex-col items-center justify-center gap-0">
      <img
        src="https://www.cvale.com.br/site/web-files/imagens/icones-clima/IsoRainSwrsDay.png"
        alt=""
      />``
      <p class="text-white text-[120px] mt-[-40px] font-bold">
        15 <span class="text-[50px] font-normal ml-[-30px]">°C</span>
      </p>
      <h2 class="text-[36px] text-[#A09FB1] mb-[10px]">Shower</h2>
    </div>

    <!-- footer -->

    <div class="flex flex-col items-center justify-center gap-[10px]">
      <div class="flex flex-row items-center gap-6">
        <p class="text-[#A09FB1] font-semibold text-[16px]">Today</p>
        <p class="text-[#A09FB1] font-bold text-[20px]">.</p>
        <p class="text-[#A09FB1] font-semibold text-[16px]">Tue, 28th Feb</p>
      </div>
      <!-- icon -->
      <div class="flex flex-row items-center gap-4">
        <font-awesome-icon
          icon="fa-solid fa-location-dot"
          class="text-[#A09FB1] font-bold text-[18px]"
        />
        <p class="text-[#A09FB1] font-bold text-[18px]">Location</p>
      </div>
    </div>
  </div>
</template>

<script setup></script>

<!-- <style lang="scss" scoped></style> -->
