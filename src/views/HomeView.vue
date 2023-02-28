<script setup>
import LeftView from "../components/LeftView.vue";
</script>

<template>
  <main class="p-0 m-0 h-screen w-screen">
    <div class="flex flex-col md:flex-row justify-between">
      <div
        class="w-screen md:w-[459px] h-screen bg-[#1E213A] px-3 py-3 md:px-[46px] md:py-[42px]"
      >
        <LeftView />
      </div>
      <div class="bg-[#100E1D]">
        <h1 class="text-white">This is the right side</h1>
        <p class="text-white">
          Lorem ipsum dolor sit amet consectetur adipisicing elit. Consectetur
          adipisci velit quae nemo nulla, inventore, fuga, recusandae cumque
          iure vel vero repudiandae? Ipsam, quo!
        </p>
      </div>
    </div>
  </main>
</template>
