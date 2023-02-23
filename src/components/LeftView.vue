<template>
  <div>
    <div class="flex flex-row justify-between items-center mb-[76px]">
      <input
        type="text"
        placeholder="Search for places"
        class="px-[11px] py-[14px] border-none text-center bg-gray-600 text-white-800 font-medium"
      />
      <div
        class="rounded-full h-[30px] w-[30px] bg-gray-600 flex justify-center items-center"
      >
        <div class="h-[15px] w-[15px] bg-white rounded-full"></div>
      </div>
    </div>

    <!-- middle -->
    <div>
      <img
        src="https://www.premiermarinas.com/assets/img/weather-icons/large/IsoRainSwrsDay.png"
        alt=""
      />
      <p>15 degree celcius</p>
      <span>Shower</span>
    </div>

    <!-- footer -->

    <div>
      <div>
        <p>Today</p>
        <p>Time</p>
      </div>
      <!-- icon -->
      <p>Location</p>
    </div>
  </div>
</template>

<script setup></script>

<!-- <style lang="scss" scoped></style> -->
