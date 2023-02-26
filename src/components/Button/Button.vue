<template>
  <button
    class="flex h-[24px] bg-orange-400 rounded text-xxs text-orange-900 px-[6px] py-[2px]"
    v-bind="$attrs"
  >
    <slot></slot>
  </button>
</template>
<script lang="ts" setup></script>
<script lang="ts">
export default {
  name: "PButton",
};
</script>
