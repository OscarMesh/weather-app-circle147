<script setup>
import LeftView from "../components/LeftView.vue";
import RightView from "../components/RightView.vue";
</script>

<template>
  <main class="p-0 m-0 h-screen w-screen">
    <div class="flex flex-col md:flex-row justify-between">
      <div
        class="w-screen md:w-[459px] h-screen bg-[#1E213A] px-3 py-3 md:px-[46px] md:py-[42px]"
      >
        <LeftView />
      </div>
      <div class="bg-[#100E1D] w-screen h-screen px-3 py-3 md:px-[123px] md:py-[42px]">
        <RightView />
      </div>
    </div>
  </main>
</template>
