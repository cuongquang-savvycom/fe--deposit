<template>
  <div class="flex pt-6 pb-[48px] bg-neutral-300">
    <div
      class="flex flex-col pt-6 pb-8 w-[672px] mx-auto rounded-lg border border-blue-300 shadow bg-white"
    >
      <div class="flex flex-row px-6 mb-6 justify-between items-center">
        <span class="text-2xl font-bold">POOL</span>
        <div class="flex flex-row gap-2">
          <Input placeholder="Token name">
            <template #input-prepend>
              <img
                class="w-[16px] h-[16px]"
                src="@/assets/search.svg"
                alt="Sort Icon"
              />
            </template>
          </Input>
          <div
            class="flex rounded-md min-w-[32px] min-h-[32px] items-center justify-center border border-neutral-400 hover:cursor-pointer"
          >
            <img
              class="w-[20px] h-[20px]"
              src="@/assets/sort.svg"
              alt="Sort Icon"
            />
          </div>
        </div>
      </div>
      <div class="flex flex-col py-4 px-6 gap-6">
        <div class="flex flex-row justify-between">
          <div class="flex items-center">
            <div class="flex gap-1">
              <img
                class="rounded-full shadowed object-contain h-[24px] w-[24px]"
                src="@/assets/stone.svg"
                alt="Stone logo"
              />
              <img
                class="rounded-full shadowed object-contain h-[24px] w-[24px]"
                src="@/assets/icons/tokens/klay.png"
                alt="Stone logo"
              />
            </div>
            <span class="flex ml-4 font-bold leading-[23px]">
              STONE / KLAY
            </span>
            <Tag class="ml-4 font-semibold">0.2%</Tag>
            <TagBase class="ml-4 font-semibold leading-[12px]">STONE</TagBase>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>

<script lang="ts" setup>
import Input from "@/components/Input/Input.vue";
import Tag from "@/components/Tag/Tag.vue";
import TagBase from "@/components/Tag/TagBase.vue";
</script>
