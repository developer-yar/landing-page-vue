<template>
  <footer class="footer">
    <SectionLabelText text="©2015-2024 Company Name" />
  </footer>
</template>

<script setup lang="ts">
import SectionLabelText from "@/components/SectionLabelText.vue";
</script>

<style lang="scss" scoped>
.footer {
  background-color: var(--dark-gray);
  block-size: 125px;
  display: grid;
  place-content: center;
}
</style>
