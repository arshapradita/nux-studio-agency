<script setup></script>

<template>
  <div
    class="w-full h-[90px] border-b border-black flex justify-between box-border px-8 items-center"
  >
    <div class="w-[112px] h-[32px] box-border flex justify-between">
      <div
        class="w-[32px] h-[32px] cursor-pointer hover:-translate-y-1 transition ease-in delay-0"
      >
        <img
          src="./assets/icon-instagram.png"
          alt="icon-instagram"
          class="w-full"
        />
      </div>
      <div
        class="w-[32px] h-[32px] cursor-pointer hover:-translate-y-1 transition ease-in delay-0"
      >
        <img
          src="./assets/icon-dribbble.png"
          alt="icon-dribble"
          class="w-full"
        />
      </div>
      <div
        class="w-[32px] h-[32px] cursor-pointer hover:-translate-y-1 transition ease-in delay-0"
      >
        <img src="./assets/icon-medium.png" alt="icon-medium" class="w-full" />
      </div>
    </div>
    <div class="w-[803px] h-[30px] flex justify-between items-center">
      <div class="w-[248px] h-[22px] flex justify-between items-center">
        <h1 class="text-black text-lg font-medium font-cd">Home</h1>
        <h1 class="text-black text-lg font-medium font-cd">Service</h1>
        <h1 class="text-black text-lg font-medium font-cd">Project</h1>
      </div>
      <div class="w-[126px] h-[30px]">
        <h1
          class="text-black text-2xl font-semibold uppercase font-cd tracking-tight"
        >
          Nuxdsgn.
        </h1>
      </div>
      <div class="w-[285px] h-[22px] flex justify-between items-center">
        <h1 class="text-black text-lg font-medium font-cd">Testimonials</h1>
        <h1 class="text-black text-lg font-medium font-cd">Blog</h1>
        <h1 class="text-black text-lg font-medium font-cd">Contact</h1>
      </div>
    </div>
    <div
      class="w-[148px] h-[44px] border-black border rounded-[32px] bg-black px-[24px] py-[12px] box-border cursor-pointer hover:drop-shadow-xl transition ease-in delay-75"
    >
      <h3 class="text-white font-cd text-base font-medium mt-[-2px]">
        Collaborate?
      </h3>
    </div>
  </div>
  <HelloWorld msg="Vite + Vue" />
</template>

<style scoped>
/* .logo {
  height: 6em;
  padding: 1.5em;
  will-change: filter;
  transition: filter 300ms;
}
.logo:hover {
  filter: drop-shadow(0 0 2em #646cffaa);
}
.logo.vue:hover {
  filter: drop-shadow(0 0 2em #42b883aa);
} */
</style>
