<template>
  <div
    class="flex flex-row pt-5 pb-5 pl-[40px] pr-[40px] md:pl-[72px] md:pr-[72px] bg-neutral-900 justify-between items-center"
  >
    <img src="@/assets/logo.svg" alt="App logo" />
    <div
      class="flex flex-row justify-between items-center gap-12 font-semibold hidden md:flex"
    >
      <span class="text-orange-900">POOL</span>
      <span class="text-neutral-500 hover:text-orange-900 hover:cursor-pointer"
        >SWAP</span
      >
      <span class="text-neutral-500 hover:text-orange-900 hover:cursor-pointer"
        >PORTFOLIO</span
      >
      <span class="text-neutral-500 hover:text-orange-900 hover:cursor-pointer"
        >STONE</span
      >
      <span class="text-neutral-500 hover:text-orange-900 hover:cursor-pointer"
        >DASHBOARD</span
      >
    </div>
    <span
      class="flex text-orange-900 rounded-full border-orange-900 border-[1px] justify-center text-sm font-semibold p-2 pt-1 pb-1 min-w-[160px] hidden md:flex hover:cursor-pointer"
    >
      Connect Wallet
    </span>
    <img class="show md:hidden" src="@/assets/menu.svg" alt="Menu" />
  </div>
</template>
<script lang="ts" setup></script>
