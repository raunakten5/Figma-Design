<template>
  <div :class="$style.frame" />
</template>
<script>
  import { defineComponent, ref } from "vue";

  export default defineComponent({
    name: "Frame",
  });
</script>
<style module>
  .frame {
    position: relative;
    background-color: var(--color-white);
    width: 100%;
    height: 100px;
    overflow: hidden;
  }
</style>
